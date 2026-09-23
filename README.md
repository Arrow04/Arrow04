<div align="center">

# Sayak Chattopadhyay
### **Senior Systems & Full-Stack Engineer**
*Specializing in Cyber Security, Distributed Systems, & High-Scale Enterprise SaaS*

[![Website](https://img.shields.io/badge/Portfolio-cybersentineltech.online-0055FF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.cybersentineltech.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sayak--chattopadhyay-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sayak-chattopadhyay-249849405)
[![X/Twitter](https://img.shields.io/badge/X-@sayakchatterji4-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sayakchatterji4)
[![Email](https://img.shields.io/badge/Email-chattopadhyaysayak7@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chattopadhyaysayak7@gmail.com)

---

</div>

## 📌 Executive Summary

I am a Software Systems Engineer with deep expertise in building **low-latency Go services**, **asynchronous Python backends**, and **scalable cross-platform frontends (React 19, Next.js, Flutter)**. My work focuses on solving complex engineering challenges—ranging from **autonomous threat response and SIEM telemetry** to **real-time geospatial dispatch systems** and **multi-tenant enterprise resource management engines**.

---
## 🛠️ Technical Competency Matrix

| Domain | Key Technologies & Architecture |
| :--- | :--- |
| **Languages** | ![Go](https://img.shields.io/badge/Go_1.22+-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Backend & Microservices** | ![Gin](https://img.shields.io/badge/Gin_Gonic-008080?style=flat-square&logo=go&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![REST/WebSockets](https://img.shields.io/badge/REST_&_WebSockets-0055FF?style=flat-square) |
| **Frontend & Mobile** | ![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js_14+-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter_3.38-02569B?style=flat-square&logo=flutter&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) |
| **Data & Infrastructure** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-336791?style=flat-square&logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis_7-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Security & Systems** | ![EDR/SIEM](https://img.shields.io/badge/EDR_&_SIEM-000000?style=flat-square) ![DNS Sinkhole](https://img.shields.io/badge/DNS_Sinkhole-miekg%2Fdns-00ADD8?style=flat-square) ![NVIDIA Llama](https://img.shields.io/badge/NVIDIA_Llama_3.2-76B900?style=flat-square&logo=nvidia&logoColor=white) |

---

## ⚡ Flagship Systems & Portfolio Showcase

### 🛡️ 01. Cyber Sentinel — Autonomous Threat Defense Platform
> **Domain:** Cybersecurity, EDR/SIEM, Autonomous SOAR  
> **Tech Stack:** Go 1.22 (Gin, pure CGO-free agent) | React 19 | PostgreSQL 15+ | NVIDIA Llama 3.2 | `miekg/dns`

* **The Industry Challenge:** Ransomware and threat actors move faster than human SOC teams can respond. Manual incident containment leads to catastrophic enterprise data leaks.
* **The Engineering Solution:** Built an autonomous threat response platform featuring CGO-free Go agents running directly on host endpoints. The platform continuously monitors file, process, and network activity, automatically isolating compromised hosts within milliseconds of threat detection.
* **Key Architecture & Metrics:**
  * **Scalable Microservices:** 145+ REST endpoints powered by Go and PostgreSQL managing **58,964+ live IOCs** (OSINT feeds: ThreatFox, URLhaus).
  * **AI Threat Analysis:** Integrated **NVIDIA Llama 3.2** for real-time natural language triage, playbook execution, and security recommendations.
  * **Infrastructure Security:** Custom DNS Sinkhole server (`miekg/dns`), P2P HMAC-authenticated threat sharing between agents, canary file vaults, and tamper-evident SHA-256 hash chains.

---

### 🚑 02. HelpMS — On-Demand Emergency Medical Dispatch Engine
> **Domain:** Real-Time Mobility, HealthTech, Distributed Systems  
> **Tech Stack:** Go 1.22 | Gin | GORM | PostgreSQL 16 + PostGIS | Flutter 3.38 | WebSockets | Redis | Razorpay

* **The Industry Challenge:** Emergency transport response times suffer due to fragmented fleet management, lack of real-time telemetry, and opaque pricing.
* **The Engineering Solution:** Engineered a high-concurrency dispatch system connecting patients with medical transport operators across three tiers (BLS, ALS, Hearse) with real-time location streaming and automated fare calculations.
* **Key Architecture & Metrics:**
  * **Geospatial Engine:** PostgreSQL + PostGIS with Haversine distance processing for instant nearest-driver matching.
  * **Low-Latency Telemetry:** Gorilla WebSockets backed by Redis Pub/Sub for high-throughput live location streaming to Flutter cross-platform applications.
  * **Financial Operations:** Automated Razorpay payment lifecycle with a 15% platform commission system and real-time driver wallet payouts.

---

### 🏢 03. HRMS.Pro! — Enterprise Multi-Tenant HR & Compliance Ecosystem
> **Domain:** Enterprise SaaS, Fintech, HR Tech  
> **Tech Stack:** Monorepo | FastAPI | React 19 | React Native (Expo) | PostgreSQL | Redis | Docker

* **The Industry Challenge:** Managing statutory compliance (PF, ESI, LWF, Form 16), complex leave workflows, and multi-tenant isolation across web and mobile without administrative friction.
* **The Engineering Solution:** Designed a modular multi-tenant HR workspace enforcing strict row-level isolation, automated statutory payroll processing, document OCR, and offline-capable mobile attendance tracking.
* **Key Architecture & Metrics:**
  * **`hrms_backend`**: Asynchronous FastAPI core utilizing SQLAlchemy 2.0 and Pydantic 2 with row-level `organization_id` security scoping and AI document parsing.
  * **`hrms_react_web`**: High-performance React 19 portal powered by AG Grid for efficient processing of large enterprise datasets.
  * **`hrms_mobile`**: Expo / React Native application featuring custom offline action queues and selfie-based attendance validation.

---

### 🏭 04. Multi-Tenant Enterprise ERP Core
> **Domain:** Supply Chain, Enterprise Resource Planning, Financial Accounting  
> **Tech Stack:** Python (Django) | Next.js | TypeScript | PostgreSQL | Redis | Docker

* **The Industry Challenge:** Enterprise resource management requires high transaction reliability, absolute tenant separation, and real-time operational analytics across departments.
* **The Engineering Solution:** Architected an enterprise management system utilizing Django's robust ORM for backend transaction management paired with a reactive Next.js control hub.
* **Key Architecture & Metrics:**
  * **Data Integrity & Isolation:** Custom scoping middleware ensuring secure tenant isolation and role-based access control (RBAC).
  * **High-Throughput Web Interface:** Built with Next.js and TypeScript for real-time asset tracking and executive analytics.
  * **Async Task Execution:** Integrated Redis caching and Celery/background workers to handle heavy ledger generation without locking API channels.

---


---

<div align="center">

*“Simplicity is prerequisite for reliability.”* — Edsger W. Dijkstra

</div>
