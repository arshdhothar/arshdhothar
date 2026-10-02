# Hi, I'm Arsh 👋

Computer Science student at York University (graduating 2027), based in the Greater Toronto Area. I'm looking for **software engineering and data internships for Winter or Summer 2027**.

I mostly build backend services and data-backed apps, and I like proving they work: concurrency tests, load tests, and CI that runs on every push.

## Featured projects

**[Distributed Rate Limiter](https://github.com/arshdhothar/rate-limiter)** · Java, Spring Boot, Redis, Lua, Docker, GitHub Actions, Azure
A token-bucket rate limiter backed by Redis, with an atomic Lua script so concurrent requests can never over-admit. Containerized, tested in CI against a real Redis, and deployed on Azure Container Apps. Load-tested with k6 at 499 req/s with 45 ms p95 latency and 0 errors. The load test also caught a real race condition (72 requests admitted against a 35-request limit); the README explains the root cause and the fix.

**[Job Application Analytics Platform](https://github.com/arshdhothar/job-application-tracker)** · Python, FastAPI, SQLModel, React, TypeScript · [Live demo](https://job-application-tracker-jet-rho.vercel.app/)
A FastAPI + SQLModel REST API with a React/TypeScript dashboard that tracks applications through a 4-stage pipeline, with Recharts analytics. Frontend on Vercel, backend on Render.

**[CampusCommute](https://github.com/arshdhothar/campus-commute)** · Java, Spring Boot, MySQL, JPA/Hibernate
A university ride-sharing platform built by a 5-person Agile Scrum team over 3 sprints. I was Scrum Master and built the ratings REST endpoint and the profile persistence layer.

## Tech I work with

- **Languages:** Java, Python, SQL, TypeScript, JavaScript
- **Backend & data:** Spring Boot, FastAPI, Redis, MySQL, SQLite, Azure SQL, JPA/Hibernate, SQLAlchemy
- **Infrastructure & testing:** Docker, GitHub Actions, Azure Container Apps, JUnit 5, JaCoCo, k6

## Contact

[LinkedIn](https://www.linkedin.com/in/arsh-dhothar-918227388/) · [dhothar.arsh@gmail.com](mailto:dhothar.arsh@gmail.com)
