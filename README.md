# REST API Testing Project

## Learning Objectives

* Learn usage of Spring Boot for testing REST API
* Applying TDD method
* Practicing JUnit and Mockito

## Description

Testing API part of a project by using Spring Boot framework, JUnit, Mockito, MockMvc, H2 Embedded DB and SQL. I have experience in testing REST API's by using Rest Assured and now I found a new way of doing that with Spring Boot and to be honest I found it very useful and easy


## How to Install and Run the Project
1. Clone the repository to your local machine 
    `git clone https://github.com/Ezzerof/RestApiTestingProject.git`
2. Open the project in your preferred IDE.
3. Run `java test package` to start the application.

## Requirements

* Java(17)
* Git
* Spring boot
* H2 DB

## Dependencies

* Spring Boot web
```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
* Spring Boot test
```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-test</artifactId>
	<scope>test</scope>
</dependency>
```
* MySQL java connector
```
<dependency>
	<groupId>mysql</groupId>
	<artifactId>mysql-connector-java</artifactId>
	<scope>runtime</scope>
</dependency>
```
* Spring data jpa
```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
```
* H2 database
```
<dependency>
	<groupId>com.h2database</groupId>
	<artifactId>h2</artifactId>
	<scope>runtime</scope>
</dependency>
```
