# Prerequisites

- Java is installed
- Docker or Docker Desktop is installed

# Start MySql

`docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=password -d mysql:latest`

# Start Spring Boot Application

`./gradlew :bootRun`

or

`.\gradlew.bat :bootRun`