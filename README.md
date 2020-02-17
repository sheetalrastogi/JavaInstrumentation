# JavaInstrumentation
Working with Java Instrumentation 

## Clone the project
from root folder, execute following to test for Java Instrumentation

mvn clean install
java -javaagent:./target/JavaInstrumentationExample-0.0.1-SNAPSHOT.jar  com.oliver.javaagent.helloworldagent.Client

Output:

Hello World! Java Agent
Hello World! Client
