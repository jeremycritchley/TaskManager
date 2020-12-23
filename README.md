# TaskManager
This web application allows software developers to create, delegate, monitor, and remove tasks that have been assigned through the Scrum Framework. 

## Roles and Responsibilities
Hosted project on an EC2 instance via Amazon Web Services.
Hosted Database on Amazon Web Services using the Relational Database Service.
Practiced Agile and Scrum methodologies to achieve weekly sprints.
Leveraged Git to implement continuous integration and development with other team members.
Leveraged Angular Materials for interactive and dynamic web content to the user interface.
Researched and leveraged the Open Weather API.
Utilized proper DevOps practices by leveraging Github and Slack to communicate effectively.
Implemented DAO design pattern to persist to a PostgreSQL database.
Utilized JUnit to run unit integration tests.
Created Angular components, modules, and services to interact with the SPA.
Deployed a functioning Java application with Angular, Spring, AWS and Tomcat server.

## Technologies
Agile-Scrum, Java, Angular 2+, PostgreSQL, Hibernate, AWS RDS, JUnit4, Mockito, Spring Test, Log4J, Spring MVC

## Getting Started on LocalHost 
#### - EC2 has been stopped due to cost
- The applicationContext.xml will need to be configured to a database with a url, username, and password
  > project-2/src/main/webapp/applicationContext.xml
- After database has been configured, run the MainDriver class as a Java Application
  > project-2/src/main/java/demo/MainDriver.java
- Run the project on a Tomcat Server (preferabbly version 8.5)
- Access the website at http://localhost:4200/
- Login as a Software Manager with:
  > username: manager   
  > password: password
- Create an account with your preferred information to access the employee page
