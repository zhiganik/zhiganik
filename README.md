# Hi, I'm Mykyta 👋

ASP.NET developer focused on clean architecture and REST APIs.

## Tech
`C#` `.NET 9/10` `ASP.NET Core` `Entity Framework Core` `ADO.NET` `PostgreSQL` `T-SQL / SQL Server` `Redis` `RabbitMQ` `MassTransit` `SignalR` `Azure Storage Account` `Docker` `NUnit`

## Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [TaskFlow](https://github.com/zhiganik/TaskFlow) | REST API with a distributed microservice backend — five independent workers communicating via RabbitMQ (file processing, avatar processing, real-time notification dispatch, email delivery, scheduled archiving). Workspace-scoped RBAC with roles resolved per-request via ASP.NET Core policy handlers, two-level hybrid cache (L1 MemoryCache + L2 Redis), cursor pagination, SignalR notifications, and pluggable file storage swappable between local disk and S3-compatible R2. | ASP.NET Core 9, EF Core, PostgreSQL, Redis, SignalR, MassTransit, RabbitMQ, S3/R2, Docker, Serilog |
| [Conference Room Booking API](https://github.com/zhiganik/conference-room-booking-api) | REST API for booking conference rooms with time-banded dynamic pricing (peak/off-peak surcharges and discounts, prorated per minute across bands) and optional paid services. Built on raw ADO.NET against Azure SQL (Entra ID auth, no passwords, stored procedures only — no ORM, no inline SQL), with DbUp-managed schema/procedure migrations that run on startup. A separate background microservice sends hourly booking reports to Telegram, with report snapshots archived to Azure Blob Storage. | ASP.NET Core 10, ADO.NET, Azure SQL, DbUp, JWT, FluentValidation, Azure Blob Storage, Docker |

## Contact
[GitHub](https://github.com/zhiganik)
