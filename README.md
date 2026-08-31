# Mirbek Abdulamitov

**Full-Stack Developer** — Bishkek, Kyrgyzstan · Open to remote, hybrid, or relocation

I build production web applications with TypeScript, Next.js, and Nest.js, backed by PostgreSQL and Prisma. Most of my work sits on the backend side of full-stack: transactional logic, data integrity, real-time sync, and authentication.

---

### What I work with

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Frontend** · JavaScript (ES6+) · TypeScript · React · Next.js (App Router, Server Actions) · Zustand · Tailwind CSS · Framer Motion<br>
**Backend** · Node.js · Nest.js · Express · Python (Flask) · REST APIs<br>
**Data** · PostgreSQL · Prisma ORM · transactions, indexing, query optimization<br>
**Infra** · Docker · Vercel · Pusher (WebSockets) · Git

---

### Selected work

**Grayton — CRM / PMS platform**
A commercial booking and property-management system built with Next.js, PostgreSQL, and Prisma. The core problem was concurrent bookings: two operators reserving the same room at the same moment. I solved it with database-level atomic transactions rather than application-layer checks, which removed the race condition entirely. The interface pairs a state-synchronized booking grid with interactive SVG floor maps, and Pusher pushes room-status changes to every connected operator in real time. Notifications run through a containerized Telegram bot.

**Security-focused services**
Backend services with custom middleware for rate limiting, strict Content Security Policies, and JWT cookie authentication. Sensitive comparisons use `crypto.timingSafeEqual` to avoid leaking information through response timing.

**TMDB Movie Platform**
A media discovery app built on the TMDB API, focused on fast client-side rendering and clean global state management.

**Navis**
Commercial marketing sites built for traffic and responsiveness, with Tailwind CSS and Framer Motion handling the interaction layer.

---

### Currently

Going deeper on Nest.js architecture — modules, dependency injection, guards, and interceptors — and on database performance work.

---

📫 **mmrek07@gmail.com** · [LinkedIn](https://linkedin.com/in/mirbek-abdulamitov) · English B2
