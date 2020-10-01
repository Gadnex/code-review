# Code Review Test

## Code Specification
Build a REST service using Spring Boot and an in memory H2 database that exposes the following methods:
 - Add Invoice --> POST http://localhost:8080/invoices
 - View All invoices --> GET http://localhost:8080/invoices
 - View Invoice --> GET http://localhost:8080/invoices/{invoiceId}

Here is a class diagram showing the most important classes:
![](Class%20Diagram.png)