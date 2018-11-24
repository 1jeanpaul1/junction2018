# Junction 2018
Project for Junction 2018 Hackathon

### Tech
1. Framework: Spring
2. Languages: Java, HTML, Javascript, css
3. Build: Gradle

### Dev
* To start the application run the following command:
   * ```$ mvn package && java -jar target/gs-spring-boot-0.1.0.jar```

* Test health of app; open a new tab and run the following command
   * ```$ curl localhost:8081/actuator/health```
   * Should return {"status":"UP"}
 
* Test REST API; open a new tab and run the following command
   * ```$ curl localhost:8081```
   * Should return: SUSTAINABILITY!!!

