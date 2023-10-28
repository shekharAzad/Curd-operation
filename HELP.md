# Read Me First
The following was discovered as part of building this project:

* The JVM level was changed from '1.8' to '17', review the [JDK Version Range](https://github.com/spring-projects/spring-framework/wiki/Spring-Framework-Versions#jdk-version-range) on the wiki for more details.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.5/reference/htmlsingle/index.html#web)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.1.5/reference/htmlsingle/index.html#using.devtools)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)


###API Endpoints
Provide detailed information about the API endpoints for creating, reading, updating, and deleting employees. Include examples of request and response payloads.

GET /employees: Retrieve a list of all employees.
GET /employees/{id}: Retrieve a single employee by ID.
POST /employees: Create a new employee.
	Request Body: JSON representing the employee details.
	{
	  "name": "John Doe",
	  "email": "john.doe@example.com"
	}
		
PUT /employees/{id}: Update an existing employee.
	Request Body: JSON representing the updated employee details.
	{
	  "name": "Updated Name",
	  "email": "updated.email@example.com"
	}
	
DELETE /employees/{id}: Delete an employee by ID.

