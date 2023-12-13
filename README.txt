Command to build : 
./gradlew build
Comand to launch : 
./gradlew bootrun

To launch the server locally: 
./gradlew bootJar
java -jar filepath

To launch the server on docker
Create the dockerfile
docker build --tag=server:latest .
docker run -d -p 8080:8080 server