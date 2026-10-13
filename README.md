<div align="center">

<img src="https://github.com/Osama-matter.png?size=200" width="110" alt="Osama Mattar"/>

# Osama Mattar

### Backend Developer · ASP.NET Core · Clean Architecture

*I build secure, multi-tenant .NET backends that are ready for production.*

`.NET 8` · `CQRS` · `EF Core` · `SQL Server` · `Hangfire`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=7C3AED)](https://www.linkedin.com/in/osama-mattar-86511b341)
[![Email](https://img.shields.io/badge/Email-0A0A1A?style=for-the-badge&logo=gmail&logoColor=A78BFA)](mailto:your.email@example.com)
[![Live Project](https://img.shields.io/badge/Live_in_Production-0A0A1A?style=for-the-badge&logo=azurepipelines&logoColor=34D399)](https://aquacheckdigitalplatform.runasp.net/)
![Open to work](https://img.shields.io/badge/Open_to_Work-Backend_.NET-34D399?style=for-the-badge&labelColor=0A0A1A)

</div>

---

## 👋 About me

CS student and backend developer focused on **ASP.NET Core 8**, **Clean Architecture** and **CQRS**.
I don't just build CRUD APIs. I design the domain model, secure it (JWT + RBAC), and make it reliable (background jobs, structured logging).

- 🚀 **Shipped to production:** a real platform used by real users ([AquaCheck](https://aquacheckdigitalplatform.runasp.net/))
- 🏗️ **Currently building:** ClinicFlow, a multi-tenant SaaS for clinic management
- 🧠 **Philosophy:** *Make it work, make it right, make it fast, in that order.*

---

## 🧰 Tech Stack

![C#](https://img.shields.io/badge/C%23-0A0A1A?style=for-the-badge&logo=c-sharp&logoColor=7C3AED)
![.NET 8](https://img.shields.io/badge/.NET_8-0A0A1A?style=for-the-badge&logo=dotnet&logoColor=A78BFA)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-0A0A1A?style=for-the-badge&logo=dotnet&logoColor=C4B5FD)
![EF Core](https://img.shields.io/badge/EF_Core-0A0A1A?style=for-the-badge&logo=dotnet&logoColor=A78BFA)
![SQL Server](https://img.shields.io/badge/SQL_Server-0A0A1A?style=for-the-badge&logo=microsoft-sql-server&logoColor=7C3AED)
![MediatR](https://img.shields.io/badge/MediatR_CQRS-0A0A1A?style=for-the-badge&logoColor=white)
![Hangfire](https://img.shields.io/badge/Hangfire-0A0A1A?style=for-the-badge&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-0A0A1A?style=for-the-badge&logo=json-web-tokens&logoColor=7C3AED)
![Swagger](https://img.shields.io/badge/Swagger-0A0A1A?style=for-the-badge&logo=swagger&logoColor=A78BFA)
![Git](https://img.shields.io/badge/Git-0A0A1A?style=for-the-badge&logo=git&logoColor=A78BFA)

---

## ⭐ Flagship Project

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

`ASP.NET Core 8` `EF Core` `SQL Server` `MediatR` `Hangfire` `Serilog`

---

## 🚀 Live in Production

### 🌊 [AquaCheck Digital Platform](https://aquacheckdigitalplatform.runasp.net/)

> End-to-end operations platform for a dive center, **deployed and used by real users**.

- E-signature integration + automated PDF generation
- Centralized digital record management

`ASP.NET MVC` `PDF Generation` `Digital Signatures`

---

## 🏗️ More Projects

| Project | What it shows | Stack |
|---|---|---|
| 🍔 [**Food Delivery System**](https://github.com/Osama-matter/Delivery-System) | Clean Architecture + CQRS, JWT + role-based auth, full order & delivery lifecycle, Swagger docs | `ASP.NET Core 8` `EF Core` `SQL Server` |
| 🛍️ [**Mega Matter E-Commerce**](https://lnkd.in/gyXhnwnM) | Real payments (PayPal API v2), cart + checkout flow, 18,000+ lines, built in 3 weeks | `ASP.NET MVC` `PayPal` `Bootstrap` |
| 🎓 [**EduPlatform LMS**](https://github.com/Osama-matter/Educational_Platform_Backend) | Multi-role LMS: courses, student progress, multi-tier auth | `ASP.NET Core` `EF Core` `JWT` |
| 🏭 [**Industrix**](https://github.com/Osama-matter/Industrix) | Inventory microservice with real-time state, analytics and reporting endpoints | `Microservices` `.NET Core` `SQL Server` |
| 🏨 [**Hotel Booking API**](https://github.com/Osama-matter/Hotel-Bokking-System) | Reservation CRUD, JWT + RBAC, repository pattern | `REST API` `JWT` `EF Core` |
| 🚍 [**Transportation Booking**](https://github.com/AbdoSol1iman/Transportation-booking-) | Full-stack: atomic seat booking, RBAC, booking history | `Angular` `Node.js` `MongoDB` |

---

## 💡 How I build

- **Domain first:** I model the business before touching the framework.
- **Separation of concerns:** layers that can be tested and swapped independently.
- **Secure by default:** authentication, authorization and tenant isolation from day one.
- **Documented APIs:** every endpoint is described in Swagger so others can use it immediately.

---

## 🌱 Learning next

🐳 Docker · ☁️ Azure · 🎨 Angular · 🏗️ Distributed systems patterns

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Osama-matter&show_icons=true&hide_border=true&bg_color=0A0A1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Osama-matter&layout=compact&hide_border=true&bg_color=0A0A1A&title_color=A78BFA&text_color=C4B5FD" />

<img src="https://streak-stats.demolab.com?user=Osama-matter&theme=midnight-purple&hide_border=true&background=0A0A1A&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD" />

</div>

---

## 💼 Let's work together

I'm looking for a **backend role (.NET)** where clean architecture and engineering discipline matter.
If you're building something serious, **let's talk**.

<div align="center">

[![Email](https://img.shields.io/badge/Email_Me-0A0A1A?style=for-the-badge&logo=gmail&logoColor=7C3AED)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/Connect-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://www.linkedin.com/in/osama-mattar-86511b341)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:4c1d95,100:1e1b4b&height=100&section=footer" width="100%"/>

</div>
