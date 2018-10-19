# spring-boot-rest-services
spring boot RESTful services, I just use couple Celtics players as default data.

### To run the service on a users laptop (in Windows environment)
- Unzip the zip file
- Open Command Prompt and Change directory (cd) to folder containing pom.xml
   - mvn package
   - java -jar target/player-services-0.0.1-SNAPSHOT.jar
- To manually test this, I use a Firefox plugin (RESTClient) to send GET/PUT/DELETE/POST request to the controller.
   - remember to set the content type in the header to application/json
- You are all Set
