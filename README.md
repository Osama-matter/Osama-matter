<div align="center">

<img src="assets/header.svg" width="100%" alt="Osama Mattar - Backend Developer"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://www.linkedin.com/in/osama-mattar-86511b341)
[![Email](https://img.shields.io/badge/Email-0A0A1A?style=for-the-badge&logo=gmail&logoColor=7C3AED)](osamamatter390@gmail.com)
[![Live Project](https://img.shields.io/badge/Live_Project-MatterHub-0A0A1A?style=for-the-badge&logoColor=34D399&labelColor=0A0A1A&color=34D399)](https://mattar-dev.vercel.app/)
[![Open to work](https://img.shields.io/badge/Open_to_work-Backend_.NET-0A0A1A?style=for-the-badge&labelColor=0A0A1A&color=7C3AED)](mailto:osamamatter390@gmail.com)

<img src="assets/control.svg" width="85%" alt="Profile control panel"/>

[ClinicFlow](https://github.com/Osama-matter/Clinic-appointment-management.git) &nbsp;|&nbsp; [MatterHub (Live)](https://mattar-dev.vercel.app/) &nbsp;|&nbsp; [All projects](#-projects) &nbsp;|&nbsp; [Contact](#-contact)

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_about.svg" width="100%" alt="About"/>

</div>

I'm a CS student and backend developer who builds **production-grade .NET systems**, not just CRUD APIs.
I design the domain model first, secure it with **JWT + RBAC**, and make it reliable with **background jobs and structured logging**.

- 🚀 **Shipped:** [MatterHub](https://mattar-dev.vercel.app/), a live platform serving real users
- 🏗️ **Building:** ClinicFlow, a multi-tenant SaaS for clinic management
- 🧠 **Principle:** *Make it work, make it right, make it fast, in that order.*

<div align="center">

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_stack.svg" width="100%" alt="Tech stack"/>

<img src="assets/tech.svg" width="90%" alt="Tech stack grid"/>

<sub>🌱 Learning next: Docker · Azure · Distributed systems patterns</sub>

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_flagship.svg" width="100%" alt="Flagship project"/>

</div>

### 🏥 [ClinicFlow: Multi-Tenant SaaS for Clinic Management](https://github.com/Osama-matter/Clinic-appointment-management.git)

> Enterprise-grade platform where each clinic (tenant) gets isolated data, roles and workflows.

| | |
|---|---|
| **Architecture** | Clean Architecture + CQRS (MediatR), fully multi-tenant |
| **Security** | JWT + fine-grained RBAC across tenant boundaries |
| **Reliability** | Hangfire background jobs, Serilog structured logging |
| **API** | 15+ documented REST endpoints (Swagger / OpenAPI) |

```mermaid
flowchart LR
    A[Client] --> B[API Layer]
    B -->|Commands / Queries| C[MediatR]
    C --> D[Application Handlers]
    D --> E[Domain Model]
    D --> F[(SQL Server via EF Core)]
    G[Hangfire Jobs] --> D
```

<div align="center">

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_live.svg" width="100%" alt="Live in production"/>

</div>

### 🌊 [AquaCheck Digital Platform](https://aquacheckdigitalplatform.runasp.net/)

> End-to-end operations platform for a dive center, **deployed and used by real users**.

- E-signature integration + automated PDF generation
- Centralized digital record management

`ASP.NET MVC` `PDF Generation` `Digital Signatures`

<div align="center">

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_projects.svg" width="100%" alt="Projects"/>

</div>

<a id="-projects"></a>

| Project | What it shows | Stack |
|---|---|---|
| 🍔 [**Food Delivery System**](https://github.com/Osama-matter/Delivery-System) | Clean Architecture + CQRS, JWT + role-based auth, full order & delivery lifecycle, Swagger docs | `ASP.NET Core 8` `EF Core` `SQL Server` |
| 🛍️ [**Mega Matter E-Commerce**](https://lnkd.in/gyXhnwnM) | Real payments (PayPal API v2), cart + checkout, 18,000+ lines, built in 3 weeks | `ASP.NET MVC` `PayPal` `Bootstrap` |
| 🎓 [**EduPlatform LMS**](https://github.com/Osama-matter/Educational_Platform_Backend) | Multi-role LMS: courses, student progress, multi-tier auth | `ASP.NET Core` `EF Core` `JWT` |
| 🏭 [**Industrix**](https://github.com/Osama-matter/Industrix) | Inventory microservice with real-time state, analytics and reporting endpoints | `Microservices` `.NET Core` `SQL Server` |
| 🏨 [**Hotel Booking API**](https://github.com/Osama-matter/Hotel-Bokking-System) | Reservation CRUD, JWT + RBAC, repository pattern | `REST API` `JWT` `EF Core` |
| 🚍 [**Transportation Booking**](https://github.com/AbdoSol1iman/Transportation-booking-) | Full-stack: atomic seat booking, RBAC, booking history | `Angular` `Node.js` `MongoDB` |

<div align="center">

<img src="assets/divider.svg" width="100%" alt=""/>

<img src="assets/sec_stats.svg" width="100%" alt="Statistics"/>

<img src="https://streak-stats.demolab.com?user=Osama-matter&theme=midnight-purple&hide_border=true&background=0A0A1A&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD" alt="Streak"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=Osama-matter&show_icons=true&hide_border=true&bg_color=0A0A1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD" height="170" alt="Stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Osama-matter&layout=compact&hide_border=true&bg_color=0A0A1A&title_color=A78BFA&text_color=C4B5FD" height="170" alt="Top languages"/>

<img src="assets/divider.svg" width="100%" alt=""/>

<a id="-contact"></a>

<img src="assets/sec_contact.svg" width="100%" alt="Contact"/>

I'm looking for a **backend role (.NET)** where clean architecture and engineering discipline matter.<br/>
If you're building something serious, let's talk.

[![Email](https://img.shields.io/badge/Email_Me-0A0A1A?style=for-the-badge&logo=gmail&logoColor=7C3AED)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/Connect-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://www.linkedin.com/in/osama-mattar-86511b341)

<img src="assets/divider.svg" width="100%" alt=""/>

</div>
