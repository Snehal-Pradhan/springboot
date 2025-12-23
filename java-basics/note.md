### Java

java is known for its "Write Once Run Anywhere" capability.
java can run in any platform if jvm is present

##### JDK,JRE and JVM
JDK when installed, JRE and JVM are also added.

- JDK is `java developement kit` is a comprehensive software which has everything needed to develope a java program.
it includes
1. the `java` compiler -> `javac` which converts javasource code to bytecode (`.java` files -> `.class` files).
2. development tools like debugger,documentation generator (javadoc)
3. source files for java core
4. the `JRE`

- JRE is the `java runtime environment`, needed to run java on a computer 
it includes
1. compiled classes like (String,Integer,ArrayList) and configuration files that tell java how to run.
2. no development tools
3. JRE can be installed only if you need to run java files, no development. as needs JDK

- JVM is `java virtual machine` that makes it possible to run the bytecode in any environment.

---

#### Summary
- JDK contains JRE ,which contains JVM
- developer needs JDK to create java applications
- end user only needs JRE to run the code.
- JVM is the actual engine which runs java bytecode on any platform.

---
1. source code is written in .java files.
2. compilation transforms it into platform independent bytecode. in .class files
3. execution is handles by jvm turning to machine code.

---
