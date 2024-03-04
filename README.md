--How to initialize websocket for correrjuntos project--

1- Clone the project

2- Type mvn package in the terminal

3- Type mvn install dependency:copy-dependencies in the terminal

4- Go to /src/main/java directory

5- Type javac -cp .:../../../target/dependency/Java-WebSocket-1.5.4.jar:../../../target/dependency/junit-4.11.jar:../../../target/dependency/slf4j-api-2.0.6.jar com/mycompany/chatserver/ChatServer.java

5- Type java -cp .:../../../target/dependency/Java-WebSocket-1.5.4.jar:../../../target/dependency/junit-4.11.jar:../../../target/dependency/slf4j-api-2.0.6.jar com/mycompany/chatserver/ChatServer.java

6- Enjoy websocket!