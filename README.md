# Hi, I'm Mykyta 👋

ASP.NET developer focused on clean architecture and REST APIs.

## Tech
`C#` `.NET 9/10` `ASP.NET Core` `Entity Framework Core` `PostgreSQL` `Redis` `RabbitMQ` `MassTransit` `SignalR` `S3 / R2` `Docker` `NUnit` `Serilog`

## Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [TaskFlow](https://github.com/zhiganik/TaskFlow) | Kanban task-management platform — clean-architecture ASP.NET Core 9 REST API with workspace-scoped RBAC (Owner / Admin / Member resolved per-request via policy handlers), cursor pagination, real-time SignalR notifications, file attachments via pluggable `IBlobService` (local disk / S3-compatible R2), two-level hybrid cache (L1 MemoryCache + L2 Redis), async messaging with MassTransit + RabbitMQ, and a separate Archive Worker microservice. Full Docker stack with structured JSON logging (Serilog + SEQ). | ASP.NET Core 9, EF Core, PostgreSQL, Redis, SignalR, MassTransit, RabbitMQ, S3/R2, Docker, Serilog |
| [Tandur Backend](https://github.com/zhiganik/tandur_backend) | Clean Architecture REST API for a restaurant platform — dual JWT auth (mobile OTP + admin email/password), Stripe payments, orders, soft-deletable entities, deployed via Docker + CI/CD to a VPS | ASP.NET Core, EF Core, PostgreSQL, Redis, Docker |
| [BookingHack](https://github.com/zhiganik/BookingHack) | Sandbox API for practicing backend patterns — JWT auth with Redis-backed refresh token rotation, company & role-based membership management | ASP.NET Core, EF Core, PostgreSQL, Redis, NUnit |
| [SecurityGrade](https://github.com/zhiganik/SecurityPractice) | Minimal API demonstrating secure web app practices — XSS/SQL-injection input sanitization, JWT auth, role-based authorization with ASP.NET Identity | ASP.NET Core, ASP.NET Identity, JWT, NUnit |

## Contact
[GitHub](https://github.com/zhiganik)
