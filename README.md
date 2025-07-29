# Bajaj Finserv Spring Boot Qualifier 1 – Webhook + SQL Task

This repository contains the solution for the Bajaj Finserv Health Backend Qualifier Round (Java – Spring Boot).

## ✅ Problem Summary

1. **Webhook Trigger**:
   - On application startup, the server makes a POST request to a given webhook endpoint.

2. **SQL Task**:
   - Three tables: `DEPARTMENT`, `EMPLOYEE`, and `PAYMENTS`.
   - Task: For each employee, find the number of employees in the same department who are **younger** than them.

## 🔧 Tech Stack

- Java 17
- Spring Boot 3.x
- Maven
- H2 (in-memory SQL database)
- JPA (Hibernate)

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
mvn spring-boot:run
java -jar release/<your-jar-file-name>.jar
