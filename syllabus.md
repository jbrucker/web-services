# Web Services for Software Developers


## Course Description

This course introduces software developers to the principles and practices of web services, focusing on RESTful architectures. Students will gain hands-on experience in designing, developing, securing, testing, and deploying APIs. Topics include service integration, asynchronous communication, API security, microservices, and documentation standards.

**Prerequisites:** Proficiency in Java or Python. Knowledge of Javascript helpful.

## Learning Objectives

By the end of the course, students will be able to:

* Understand and apply the principles of RESTful and SOAP web services
* Design, implement, and document REST APIs using OpenAPI
* Secure web services using authentication and authorization mechanisms
* Integrate external APIs into applications
* Apply testing, debugging, and deployment best practices for web services
* Develop and present an end-to-end web service project

## Assessment

**Tentative and likely to change**

* Weekly Labs: 20%
* Participation and Quizzes: 30%
* Course Project: 30%
* Exams: 20%

### [Resources](./references.md)


---

### Week 1: Introduction to Web Services

* Web services vs. web applications
* Role of APIs in software ecosystems
* HTTP protocol and URI design
* Consuming a web service

Lab: Use curl and browser tools to inspect HTTP requests/responses

### Week 2: JSON, XML, and Data Serialization

* Introduction to JSON and XML formats
* Content negotiation
* Schema validation in XML and JSON
* RSS and Atom standards 

Lab: Create a REST API that consumes and produces JSON and XML

### Week 3: RESTful Architecture and Design Principles

* REST constraints and statelessness
* HTTP methods and status codes
* Resource modeling and URI structure

Lab: Build a simple REST API (e.g. todo list) using Flask/Express/Spring Boot

Assignment: Create and deploy a service that provides REST access to CRUD operations on a database. Write a desktop client to use this service.


### Week 4: SOAP Web Services

* SOAP protocol overview and usage in Enterprise applications
* WSDL and SOAP messages
* RPC-style web services
* Service contracts and UDDI
* Comparison with RESTful services

Lab: Consume and test a public SOAP API; generate client code using tools like wsimport or WSDL2Java

### Week 5: API Documentation and OpenAPI Specification

* API documentation principles
* OpenAPI/Swagger specification and tooling
* Generating interactive API docs
* Mock servers

Lab: Write and serve an OpenAPI document for a web service

### Week 6: Authentication and Authorization

* Basic Auth, API keys
* OAuth 2.0 and OpenID Connect
* JWT (JSON Web Tokens)

Lab: Secure a REST API with JWT-based authentication and attempt to defeat it

### Week 7: Consuming and Integrating External APIs

* Making API calls
* Rate limits, restricting request scope, paging, and caching
* Error handling and retries
* Implications and strategies for external APIs

Lab: Create a service that aggregates data from multiple external APIs

### Project Proposals

By this point, students should have selected and researched an idea
for a web service project, and written a complete project proposal.  

* You are encouraged to select a topic that applies to another course you are currently taking
* You may design a service that integrates with other students' projects; that is, you consume or provide a web service that others use

We may have a "theme" for all projects. This helps with cross-learning and
makes project evaluation fairer.


### Week 8: Asynchronous Communication

* Polling, Webhooks, and long polling
* Introduction to WebSockets and SSE
* Practical use cases, performance, and trade-offs

Lab: Implement a webhook listener (receiver) and simulate event triggers

### Week 9: Testing and Debugging APIs

* Unit testing and mocks
* Integration tests
* API testing tools: Postman, Insomnia, REST Assured

Lab: Write an automated test suite for your API using a testing framework

### Week 10: API Gateways and Microservices (Introductory)

* Microservice principles and rationale
* API Gateway pattern
* Service discovery, circuit breakers

Lab: Build a minimal microservice with gateway using Docker Compose

### Week 11: Deployment and Monitoring

* REST API deployment (Docker, Heroku, AWS)
* Logging and monitoring. Tools such as ELK or Prometheus
* CI/CD pipelines for web services APIs

Lab: Deploy a REST API to a cloud platform with basic monitoring

### Week 12-14: Optional Topics and Project Work

New material may be added that is relevant to student projects,
and some time devoted to peer review of designs and implementations.

Optional topics may include:

* Web Service front-end to a database (this is quite basic and may be done in weeks 3-5)
* Consuming web services in client-side web apps, e.g. AXIOS for Javascript
* Consuming web services in mobile apps

### Week 15: Capstone Project Presentations

* Student final project demo and report
* Peer reviews and evaluation
* Discussion of scalability, security, deployment, and maintainability


### Advanced Topics or Final Projects

* gRPC and Protobuf
* GraphQL
* Service Mesh (Istio, Linkerd)
* Contract testing (Pact)
* Serverless APIs, e.g. AWS Lambda and API Gateway

