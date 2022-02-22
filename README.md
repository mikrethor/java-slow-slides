# slides


export  GRAALVM_HOME=~/.sdkman/candidates/java/22.0.0.2.r17-grl/
sdk use java 22.0.0.2.r17-grl


time java HelloWorld.java
Hello, World!
java HelloWorld.java  1.85s user 0.28s system 137% cpu 1.544 total


Après javac HelloWorld.java

time java HelloWorld
Hello, World!
java HelloWorld  0.13s user 0.04s system 111% cpu 0.153 total

installation native image

native-image HelloWorld

❯ time ./helloworld
Hello, World!
./helloworld  0.04s user 0.01s system 84% cpu 0.054 total


