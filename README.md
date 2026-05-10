# PaySight — Finance Tracker API

A REST API for tracking personal income and expenses. Built with Spring Boot, secured with JWT, backed by PostgreSQL.

---

## Stack

- Java 17 + Spring Boot 3.2
- Spring Security + JWT
- PostgreSQL (Supabase)
- Spring Data JPA + Hibernate
- Deployed on Render

---

## What it does

- Register and login with JWT-based authentication
- Add, view, and delete transactions (income or expense)
- Category-wise breakdown for dashboard charts
- Each user sees only their own data

---

## Endpoints

POST   /api/auth/register
POST   /api/auth/login

GET    /api/transactions
POST   /api/transactions
DELETE /api/transactions/{id}

GET    /api/dashboard/summary

---

## Running locally

You'll need Java 17, Maven, and PostgreSQL installed.

git clone https://gith
ub.com/Snehaa044/paysight-backend.git
cd paysight-backend
# set your DB credentials in application.properties
mvn spring-boot:run

---

## Environment variables (Render)

DB_URL
DB_USERNAME
DB_PASSWORD
JWT_SECRET

---

**Frontend repo:** github.com/Snehaa044/paysight-frontend  
**Live API:** coming soon
