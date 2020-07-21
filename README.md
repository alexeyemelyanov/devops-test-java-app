# Demo java app for DevOps test task

### Building an app

First build the java app using maven

```
mvn clean package
``` 

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)

You will see the new directory named 'target' where you can find the executable jar file

### Running

To run this app you need java of version 8 or higher

```
java -jar ./target/demo-0.0.1-SNAPSHOT.jar
``` 

By default this java app listen to the port 8080, check if it works by requesting an url

```
http://localhost:8080/
``` 

You can change the application port to 3000 by setting "server.port" as VM option (-D)