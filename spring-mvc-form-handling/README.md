# Spring MVC Form Handling Example (JSP)

A Spring Web MVC (non-Boot) application demonstrating form handling with validation, embedded Jetty server, and JSP views — built and run using Maven in Eclipse IDE.

---

## Technologies and Tools Used

- Java 11  
- Spring Web MVC 5.2.22.RELEASE  
- JSP (JavaServer Pages)  
- JSTL 1.2 (Java Standard Tag Library)  
- Hibernate Validator 6.2.5.Final (JSR-303 implementation)  
- JSR-303 Bean Validation API  
- Servlet API 4.0.1  
- Bootstrap 5.2.0 (via WebJars)  
- HSQLDB 2.7.0 (in-memory database)  
- Spring Test 5.2.22.RELEASE  
- Hamcrest 2.2 (used in unit testing)  
- JUnit 5.9 (unit testing framework)  
- Jetty Server 9.4.48.v20220622 (embedded web server)  
- Maven 3.8.6 (build and dependency management)  
- Eclipse IDE (with built-in Maven support)

---

## About the Project

This project demonstrates a Spring Web MVC form handling example using JSP and JSTL in a non-Spring Boot environment.

It shows how to build a traditional, annotation-based Spring MVC web application with full Java-based configuration, running on an embedded Jetty server.

### Main Features

- User registration form with fields like name, email, and password  
- Server-side validation using Hibernate Validator (JSR-303)  
- Form data binding using custom utility classes  
- View rendering using JSP and JSTL  
- MVC configuration via `AbstractAnnotationConfigDispatcherServletInitializer`  
- Bootstrap styling via WebJars  
- In-memory database support using HSQLDB  


---

## Core Features

- Form submission using `@ModelAttribute`  
- Input validation using Hibernate Validator  
- JSP views with JSTL tags  
- WAR packaging  
- Embedded Jetty server  
- Clean Maven project layout  
- Easily importable into Eclipse IDE

---

## How to Run

Use the following Maven commands:

```bash
mvn clean install
mvn jetty:run
http://localhost:8080/

