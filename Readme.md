<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:388bfd&height=200&section=header&text=Athish%20R%20S&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Engineer%20%7C%20Java%20%2B%20React%20%7C%20UNC%20Charlotte&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Spring+Boot+%2B+React+%7C+Production-Grade+Apps;JWT+Auth+%7C+Docker+%7C+PostgreSQL+%7C+AWS;Teaching+AI-Assisted+Dev+to+80%2B+Students+%40+UNCC;Shipped+apps+on+3+continents+before+finishing+my+Master's" alt="Typing SVG" />
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Athish_RS-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/athish-rs)
[![GitHub](https://img.shields.io/badge/GitHub-Athishrs-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Athishrs)
[![Email](https://img.shields.io/badge/Email-athishrs02%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:athishrs02@gmail.com)
[![Location](https://img.shields.io/badge/Charlotte%2C_NC-00827F?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Athishrs&color=1f6feb&style=flat-square&label=Profile+Views)

</div>

---

## 🧑‍💻 About Me

I'm a **Full-Stack Software Engineer** with a passion for building clean, scalable, production-grade systems. I'm currently completing my **M.S. in Information Technology at UNC Charlotte** (4.0 GPA, May 2026) while working as a Teaching Assistant in the College of Computing & Informatics — where I teach AI-assisted software development workflows to 80+ students every semester.

My background spans **3 continents of production experience** — from building component libraries and internal dashboards at a Chennai-based agency, to engineering data pipelines for a Formula Student racing team, to the full-stack SaaS work I do today. I'm currently focused on the **Java Full-Stack track** (Spring Boot + React + PostgreSQL), with deep hands-on experience in Docker, JWT security, REST APIs, and cloud deployment.

I treat **AI coding tools as first-class members of the stack** — I use Claude Code, Cursor, and GitHub Copilot daily, and actively teach others how to integrate them into real SDLC workflows. This isn't a side hobby; it's a core engineering discipline for me.

```
📍 Charlotte, NC          🎓 M.S. Information Technology, UNCC (GPA: 4.0)
💼 Open to Work           🔭 Building: Slotora
🧑‍🏫 TA: College of Computing & Informatics
```

---

## 🚀 Featured Projects

### 🗓️ [Slotora](https://github.com/Athishrs/slotora) — Multi-Tenant Appointment Booking Platform

> **The flagship.** A production-ready SaaS platform where any user can register a business, onboard staff and services, and accept bookings from clients.

| Layer | Stack |
|---|---|
| **Backend** | Java 21 · Spring Boot · Spring Security · JWT · JPA/Hibernate · Maven |
| **Frontend** | React · Vite · Tailwind CSS v3 · React Router · Axios · React Context |
| **Database** | PostgreSQL |
| **DevOps** | Docker · Docker Compose · Multi-stage builds · Nginx (SPA + API proxy) |
| **Deployment** | Railway (backend + DB) · Vercel (frontend) |
| **Testing** | JUnit 5 · Mockito · Testcontainers (19 tests, 0 failures) |

**What makes it real:**
- 🔐 Full JWT authentication system — `JwtService`, `JwtAuthFilter`, `SecurityConfig`, `AuthController`, refresh flow, `GlobalExceptionHandler`
- 🏢 Multi-tenant architecture — any authenticated user can create and manage their own business, staff, and services
- 📋 5 core entities: `User`, `Business`, `Service`, `Staff`, `Booking` with `BookingStatus` enum and full CRUD
- 🧪 Testcontainers spins up a real PostgreSQL instance for integration tests — no mocking the DB
- 🐳 ARM64/Apple Silicon compatible (`amazoncorretto:21-alpine`), custom Nginx config handles SPA routing + `/api/` proxy
- 🌱 `DataSeeder` populates demo data on first startup

---

### 🏠 [Roommate Harmony](https://github.com/Athishrs/Roomate-harmony-web) — Roommate Matching Web App

> Full-stack roommate finder with compatibility-based matching, protected auth flows, and a comprehensive test suite.

| Layer | Stack |
|---|---|
| **Frontend** | React 18 · Vite · Tailwind CSS · Shadcn UI |
| **Backend** | Node.js · Express.js |
| **Database** | PostgreSQL (Supabase) · Prisma ORM |
| **Auth** | JWT |
| **Testing** | Supertest · Playwright |
| **Deployment** | Vercel (frontend) · Render (backend) · Docker |

**Key features:** Prisma schema with 17 models, protected routes with JWT middleware, E2E tests with Playwright, Dockerized for consistent dev environments.

---

### 🍽️ Dishcovery — AI-Powered Recipe Discovery

> Describe what's in your fridge, get recipe suggestions powered by OpenAI. Bridges LLM reasoning with structured culinary data.

| Layer | Stack |
|---|---|
| **Frontend** | React · TypeScript · Vite |
| **Backend** | Python · FastAPI |
| **AI** | OpenAI Codex / GPT API |
| **Data** | Spoonacular REST API |

**Key feature:** Natural language input → ingredient extraction via LLM → structured recipe lookup → ranked results with nutrition info.

---

### 🛒 SmallBizz — E-Commerce Platform for Small Businesses

> Full-stack e-commerce solution with multi-auth strategies and a hybrid database architecture.

| Layer | Stack |
|---|---|
| **Backend** | Node.js · Express.js |
| **Auth** | Passport.js (local + OAuth) |
| **Database** | MongoDB + PostgreSQL (hybrid) |
| **DevOps** | Docker |

---

## 🛠️ Full Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

### Backend & APIs
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### Databases & ORM
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### Security & Auth
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)

### Testing
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-83B81A?style=flat-square&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)

### AI & Dev Tools
![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Athishrs&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Athishrs&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Athishrs&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://git.io/streak-stats)

</div>

<div align="center">

[![Athish's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Athishrs&theme=github-compact&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=Athishrs&theme=algolia&no-frame=true&row=1&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🌱 What I'm Currently Working On

```java
public class CurrentFocus {

    String[] activeProjects = {
        "Slotora — deploying to Railway + Vercel (prod)",
        "Adding Redis caching layer to Slotora",
        "LeetCode Pareto Problem Set — Trees, Heaps, Graphs"
    };

    String[] learning = {
        "Spring Batch for scheduled jobs",
        "Advanced Spring Security patterns",
        "System Design for distributed systems"
    };

    String targetRole = "Java Full-Stack Software Engineer";
    boolean openToWork = true;
}
```

---

## 💬 Let's Connect

If you're building something interesting with Spring Boot, React, or cloud-native infra — let's talk.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/athish-rs)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:athishrs02@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:388bfd,50:1f6feb,100:0d1117&height=120&section=footer" width="100%"/>
