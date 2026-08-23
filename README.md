# 👨‍💻 Rafael Pacheco

### Back-End Developer | Java & Spring Boot | Systems Analysis and Development Student

I'm a software development student from **São Paulo, Brazil**, currently pursuing a degree in **Systems Analysis and Development (ADS) at IFSP**.

My main focus is **Back-End Development with Java and Spring Boot**, with experience building REST APIs, relational database integrations, authentication and authorization mechanisms, process automation, and Full Stack applications.

I also completed a **Web Development course at Instituto da Oportunidade Social (IOS)** and continue improving my skills through practical projects, independent study, and hands-on software development.

Currently, I'm deepening my knowledge in:

- Java and Spring Boot;
- REST API design;
- Spring Security;
- JWT and OAuth2;
- JPA and Hibernate;
- PostgreSQL;
- Docker;
- automated testing;
- CI/CD;
- software architecture;
- cloud technologies and AWS.

---

# 🚀 Featured Project

## Centraliza

**Full Stack platform for centralized operational process management.**

Centraliza is a complete software ecosystem composed of three independent applications:

```text
                    Centraliza Web
              React + TypeScript + Vite
                         │
                    REST / JWT
                         │
                         ▼
                    Centraliza API
                 Java + Spring Boot
                    /           \
                   /             \
                  ▼               ▼
           PostgreSQL        ProcessBuilder
                                  │
                                  ▼
                         Python Automation
                              Selenium
```

The project combines **frontend, backend, database, security, document processing and browser automation** in a single integrated solution.

### Main Features

- JWT authentication;
- Role-Based Access Control (RBAC);
- users, roles and fine-grained permissions;
- operational dashboard;
- Call Back management;
- appointment reminders;
- appointment rescheduling;
- integrated patient search;
- PDF document processing and visualization;
- audit history and traceability;
- protected automation credentials;
- Java ↔ Python integration;
- Selenium browser automation;
- real-time automation progress tracking;
- PostgreSQL persistence;
- Flyway database migrations;
- automated backend tests;
- JaCoCo code coverage;
- GitHub Actions CI pipelines;
- OpenAPI / Swagger documentation.

### Architecture

```text
User
 │
 ▼
React + TypeScript
 │
 │ REST / JSON + JWT
 ▼
Spring Boot API
 │
 ├──────────────► PostgreSQL
 │
 └── ProcessBuilder
          │
          ▼
        Python
          │
          ▼
       Selenium
          │
          ▼
   Demo Web Environment
```

### Repositories

🔹 **Project Overview**  
https://github.com/pacheco-rfl/centraliza

🔹 **Back-End API**  
https://github.com/pacheco-rfl/centraliza-portfolio-api

🔹 **Front-End**  
https://github.com/pacheco-rfl/centraliza-portfolio-web

🔹 **Automation Module**  
https://github.com/pacheco-rfl/centraliza-portfolio-automation

> The public portfolio version uses only fictitious patients, professionals, documents, credentials and external environments.

---

# 🛠️ Tech Stack

## Back-End

<p align="left">
  <img alt="Java" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />
  &nbsp;
  <img alt="Spring Boot" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
  &nbsp;
  <img alt="Python" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
</p>

`Java` · `Spring Boot` · `Spring Security` · `REST APIs` · `JWT` · `JPA` · `Hibernate` · `Maven`

---

## Front-End

<p align="left">
  <img alt="React" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  &nbsp;
  <img alt="TypeScript" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
  &nbsp;
  <img alt="JavaScript" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
  &nbsp;
  <img alt="HTML5" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
  &nbsp;
  <img alt="CSS3" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />
</p>

`React` · `TypeScript` · `Vite` · `React Router` · `HTML` · `CSS` · `JavaScript`

---

## Databases

<p align="left">
  <img alt="PostgreSQL" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
  &nbsp;
  <img alt="MySQL" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
</p>

`PostgreSQL` · `MySQL` · `SQL` · `Flyway` · `Database Migrations`

---

## Automation

<p align="left">
  <img alt="Python" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  &nbsp;
  <img alt="Selenium" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/selenium/selenium-original.svg" />
</p>

`Python` · `Selenium` · `WebDriver` · `Browser Automation` · `Java/Python Integration`

---

## Tools & DevOps

<p align="left">
  <img alt="Git" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
  &nbsp;
  <img alt="GitHub" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
  &nbsp;
  <img alt="Docker" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
  &nbsp;
  <img alt="Postman" width="45px" src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" />
</p>

`Git` · `GitHub` · `GitHub Actions` · `Docker` · `Postman` · `OpenAPI / Swagger` · `CI/CD`

---

# 🔐 Back-End & Security

Some of the Back-End concepts I have been applying in my projects include:

- RESTful API design;
- JWT authentication;
- Spring Security;
- Role-Based Access Control;
- fine-grained permissions;
- protected endpoints;
- global exception handling;
- request validation;
- password hashing;
- encrypted sensitive information;
- database migrations;
- auditing and traceability.

In Centraliza, authorization is controlled not only by user roles, but also by specific permissions assigned to each role.

Example:

```text
Administrator
├── Manage users
├── Manage roles
├── Configure automation
├── Manage Call Backs
├── Manage reminders
└── Manage rescheduling

Operator
├── View Call Backs
├── Register contacts
├── View reminders
└── Register reminder contacts
```

---

# 🤖 Automation & System Integration

I also have experience integrating applications developed with different technologies.

In Centraliza, the Java Back-End starts a Python automation process using:

```text
Spring Boot
     │
     │ ProcessBuilder
     ▼
Python Runner
     │
     ▼
Selenium
```

The Python process reports execution progress back to the Java application through structured `stdout` messages.

Example:

```text
[CENTRALIZA_PROGRESS]
```

This allows the frontend to display:

- current execution status;
- processed records;
- successful operations;
- failed operations;
- skipped records;
- current item;
- execution progress;
- start and finish timestamps.

---

# 🧪 Testing & Code Quality

I use automated validation to improve reliability and maintainability.

In the Centraliza Back-End, the project includes:

- automated tests;
- Maven Verify;
- JaCoCo;
- PostgreSQL integration during CI;
- Flyway migration validation.

The projects also use independent GitHub Actions workflows:

```text
Frontend
npm ci
   ↓
npm run build

Backend
PostgreSQL
   ↓
Maven Verify
   ↓
Automated Tests
   ↓
JaCoCo

Automation
pip install
   ↓
Python compile validation
```

---

# 🧠 Currently Studying

I'm currently expanding my Back-End knowledge through the course:

**Spring Boot Expert: JPA, REST, JWT, OAuth2 with Docker and AWS**

My current study focus includes:

- advanced Spring Boot;
- REST API best practices;
- Spring Security;
- OAuth2;
- authentication and authorization;
- JPA and Hibernate;
- Docker;
- AWS;
- cloud deployment;
- automated testing;
- application architecture;
- scalable Back-End applications.

---

# 🎓 Education

### Systems Analysis and Development — IFSP

Currently pursuing a degree in **Systems Analysis and Development (ADS)**.

Main areas of interest:

- software development;
- databases;
- system architecture;
- Back-End development;
- software engineering.

### Web Development — Instituto da Oportunidade Social (IOS)

Completed a Web Development course covering fundamentals of web application development.

---

# 💡 Areas of Interest

I'm especially interested in working with:

```text
Java
Spring Boot
REST APIs
PostgreSQL
Software Architecture
Spring Security
System Integration
Process Automation
Docker
Cloud Technologies
```

---

# 🎯 Career Objective

My goal is to grow as a **Back-End Developer**, building reliable, maintainable and scalable applications while applying software engineering best practices.

I am particularly interested in opportunities where I can work with:

- Java and Spring Boot;
- API development;
- relational databases;
- software architecture;
- authentication and security;
- system integrations;
- process automation;
- cloud technologies.

I also enjoy understanding the complete application lifecycle, which is why I develop projects involving frontend, backend, databases and automation even though my main professional focus is Back-End development.

---

# 📫 Contact

📍 **São Paulo, Brazil**

💻 **GitHub**  
https://github.com/pacheco-rfl

💼 **LinkedIn**  
https://linkedin.com/in/rafael-pacheco-morais

📧 **Email**  
rafaelpacheco1324@yahoo.com

---

<p align="center">
  <b>Always learning, building and improving.</b>
</p>
