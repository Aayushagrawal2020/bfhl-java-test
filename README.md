# BFHL Java Qualifier Project

This Spring Boot project solves the Bajaj Finserv Health Java qualifier challenge:

- On startup: sends a webhook request
- Receives a JWT + webhook URL
- Based on regNo (even), submits a SQL query

## How to Run (if Maven is available)

```bash
.\mvnw.cmd spring-boot:run
