<h1 align="center">Hey, I'm Jose 👋</h1>

<p align="center">
  Systems Engineering Student &nbsp;·&nbsp; Fullstack & DevOps Developer &nbsp;·&nbsp; Always curious, always learning
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/joselancheros/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## About Me

I'm a 7th-semester Systems Engineering student at **Escuela Colombiana de Ingeniería Julio Garavito**. I like building backend systems and CI/CD pipelines that actually hold up in production, not just code that looks good in a demo.

The project that's taught me the most is **AIBERT**, where I owned the full lifecycle of a microservice in a real production system: domain design, REST API contracts, automated pipelines and cloud deployment on Azure. Going from *"it works on my machine"* to *"it works for someone else"* taught me more than most of my classes combined.

I also spend a lot of time learning on my own through Platzi, mostly cloud, DevOps and now getting into AI. I'm the kind of person who's always digging a bit deeper into whatever I'm working on.

---

## 🔧 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**DevOps & Cloud**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=for-the-badge&logo=sonarcloud&logoColor=white)

**Testing & Quality**

![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logoColor=white)
![JaCoCo](https://img.shields.io/badge/JaCoCo-C71A36?style=for-the-badge&logoColor=white)

---

## 🚀 Featured Projects

### [AIBERT](https://github.com/AI-BERT-BACKEND/dark-code-knights-academic-service)
*Intelligent academic planning platform, built as a real microservices system by a cross-functional student team.*

I owned the full lifecycle of the **Academic Management** service, from domain design to production deployment.

- **9 functional modules**: course management, grade registration, weighted GPA calculation, target-grade simulation, academic goals, weekly scheduling, and more
- **22 documented REST endpoints** following OpenAPI/Swagger standards, coordinated across 6+ microservice teams
- **Automated CI/CD pipeline**: compile, test, SonarCloud analysis, Docker build, Azure deploy
- **Production bugs I actually had to fix**: a Hibernate `LazyInitializationException`, Kafka env vars getting lost between Azure Container App revisions, PostgreSQL schema mismatches in QA, and a misconfigured Azure health probe on a custom port
- **891 automated tests**, **80%+ code coverage**, running stable in production QA

`Java 21` `Spring Boot 3.4.3` `PostgreSQL` `Apache Kafka` `Docker` `GitHub Actions` `Azure Container Apps` `Hexagonal Architecture` `JUnit 5` `SonarCloud`

---

### [TechCup Fútbol](https://github.com/Lanch3ros/techcup-futbol)
*Platform that automates the semester soccer tournament at ECI: registration, team management, payment verification, match tracking and real-time stats.*

Technically a team project (shoutout to JavaBurguers), but I ended up owning most of it: backend, DevOps and a good part of the frontend integration. I'm the author of the vast majority of the commits.

- Layered architecture (Controller → Service → Repository) with **Factory Method** and **Strategy** patterns to handle 5 different player types and their email validation rules
- Security stack: JWT + Google OAuth2, role-based access control, HTTPS end to end
- React SPA on the frontend, talking to the API over JSON/HTTPS
- **509 tests**, 100% instruction/line coverage with JaCoCo, **A rating across the board in SonarCloud**
- Full CI/CD pipeline with GitHub Actions and Docker
- Independently migrated the entire deployment stack from Azure to **Railway** (backend) and **Vercel** (frontend) once our student credits ran out

`Java 21` `Spring Boot` `PostgreSQL` `Docker` `GitHub Actions` `JWT/OAuth2` `React` `Railway` `Vercel`
  <i>Open to internships, freelance work, and teams that actually care about building software people want to use.</i>
</p>
