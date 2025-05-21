# BFHL Java Qualifier Project

This Spring Boot project solves the Bajaj Finserv Health Java qualifier challenge:

- On startup: sends a webhook request
- Receives a JWT + webhook URL
- Based on regNo (even), submits a SQL query

## How to Run (if Maven is available)

```bash
.\mvnw.cmd spring-boot:run

## Note

This project was developed and tested locally. A `.jar` file was not generated due to Maven not being installed on the system.

However, the project is fully Maven-ready and includes `mvnw.cmd`. Reviewers can build it using:

```bash
.\mvnw.cmd clean package

