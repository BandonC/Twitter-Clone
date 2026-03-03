Twitter Clone 

A personal full-stack project that recreates core Twitter/X features using a modern TypeScript stack: Next.js (web) + NestJS (API) + PostgreSQL (Prisma). Built with production-minded patterns (validation, auth, migrations, containerized local dev) and designed to evolve into a scalable deployment with Redis + CI/CD.

Features (MVP)
User registration & login
Create posts
View user profile + user posts
Follow / unfollow users
Like / unlike posts
Home feed (timeline)

Tech Stack
Frontend: Next.js (TypeScript)
Backend: NestJS (TypeScript), Prisma ORM
Data: PostgreSQL
DevOps: Docker + Docker Compose

Planned Enhancements
Cursor-based pagination for feeds (createdAt + id tie-break)
Redis-backed rate limiting and caching
CI pipeline + environment separation (dev/prod) with cloud deploy
