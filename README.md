# kotlin-comienzo
Fist tests of the Kotlin Programming Language

### Compile
kotlinc hello.kt -include-runtime -d hello.jar 

The `-d` option indicates the output path for generated class files which may be either a directory or a .jar file. 

The `-include-runtime` option makes the resulting .jar file self-contained and runnable by including the Kotlin runtime library in it.


