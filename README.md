# Smart Visa – Online Visa Application Portal

> **Domain:** Travel & Tourism  
> **Framework:** DNN (DotNetNuke), .NET  
> **UI:** Telerik Controls  
> **Author:** Sagarika Chakraborty — *Full Stack .NET Engineer | React.js | Web API | SQL Server*

**Smart Visa** is an online visa application platform that streamlines end‑to‑end visa processing for travelers and administrative staff. Built on the **DNN (DotNetNuke)** framework, the web portal enables application submission, document upload, status tracking, and workflow automation. The UI leverages **Telerik** components for responsive, accessible interactions.

---

## ✨ Key Features
- **Application Submission**: guided forms, dynamic steps, validation, auto‑save drafts.
- **Document Management**: uploads, previews, and verification checklists.
- **Status Tracking**: real‑time updates for *Submitted → Under Review → Additional Info → Approved/Rejected*.
- **Admin Console**: queue management, SLA tracking, bulk actions, and audit trails.
- **Responsive UI**: Telerik controls for grids, forms, and wizards.

---

## 🧱 Technology Stack
- **Platform**: DNN (DotNetNuke) on ASP.NET
- **Language**: C#
- **UI**: Telerik Web UI controls
- **Data**: SQL Server (through DNN providers/EF hybrid where applicable)
- **DevOps**: Standard IIS deployment; TFS/DevOps for versioning and CI/CD (as used)
- **Logging**: DNN logging, custom exception handlers

---

## 📁 Repository Structure
```
.
├─ README.md
└─ docs
   ├─ HLD.md
   ├─ LLD.md
   └─ architecture.png
```

---

## 🚀 Quick Start (Dev)
- Install **DNN** locally (version to match your environment) and configure site.
- Place module project(s) under `/DesktopModules/SmartVisa` (example).
- Update `web.config` connection string and DNN host settings.
- Build and deploy modules via Visual Studio; install Telerik if not bundled.

---

## 🧭 Documentation
- **HLD**: [`/docs/HLD.md`](docs/HLD.md) — architecture, modules, workflows, security.
- **LLD**: [`/docs/LLD.md`](docs/LLD.md) — module structure, pages, DAL, error handling.
- **Diagram**: [`/docs/architecture.png`](docs/architecture.png)

---

## 👩‍💻 Credits
**Sagarika Chakraborty** — DNN module development, Telerik UI, bug fixing & exception handling, production support, and workflow enhancements.
