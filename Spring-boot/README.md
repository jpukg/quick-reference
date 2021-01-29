## Remote debugging Spring Boot - Java
`java -Xdebug -Xrunjdwp:transport=dt_socket,server=y,address=8001,suspend=y -jar target/cxf-boot-simple-0.0.1-SNAPSHOT.jar`

## Remote debugging Spring Boot - Maven
`java -Xdebug -Xrunjdwp:transport=dt_socket,server=y,address=8001,suspend=y -jar target/cxf-boot-simple-0.0.1-SNAPSHOT.jar`

## Remote debugging Spring Boot - Maven Options
`export MAVEN_OPTS="-agentlib:jdwp=transport=dt_socket,address=8000,server=y,suspend=y"`

