<div align="center">
  <img src="./malki-achraf.png" alt="Achraf Malki logo" width="120" />

  <h1>Achraf Malki</h1>

  <p><strong>Software Engineer & IT Consultant</strong></p>

  <p>
    Backend architecture · Enterprise integration · Applied AI
  </p>

  <p>
    I build resilient backend systems, AI workflows, ERP integrations, and digital products
    that help businesses operate with more clarity and autonomy.
  </p>

  <p>
    Rabat, Morocco &nbsp;·&nbsp; EMSI Rabat, class of 2027 &nbsp;·&nbsp;
    Open to a PFE that can grow into a long-term engineering role
  </p>

  <p>
    <a href="https://achrafmalki.dev"><img src="https://img.shields.io/badge/Portfolio-achrafmalki.dev-111111?style=for-the-badge" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/achraf-malki"><img src="https://img.shields.io/badge/LinkedIn-Achraf%20Malki-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:achrafmalki.eng@gmail.com"><img src="https://img.shields.io/badge/Email-Let's%20talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p>
    <a href="#selected-experience">Experience</a> &nbsp;·&nbsp;
    <a href="#previzma">Public engineering project</a> &nbsp;·&nbsp;
    <a href="#toolkit">Toolkit</a>
  </p>
</div>

---

## How I think about engineering

I am most engaged when software architecture meets business reality. Before choosing a framework or drawing a service boundary, I try to understand how the organisation works, where information gets lost, what cannot fail, and which decisions the system is supposed to support.

That mindset has taken me toward backend architecture, enterprise integration, cloud delivery, and applied AI. I care about traceable workflows, clear data ownership, secure boundaries, and products that remain understandable after the first release.

Much of my work for employers and clients lives in private repositories. The experience below explains the problems and engineering decisions behind that work; [Previzma](#previzma) provides a public, inspectable example of how I build.

## Selected experience

### Nortis Studio · MAGMA

**Software Engineer, AI & Cloud** · January 2026–present

MAGMA is a B2B intelligence platform coordinating concurrent AI workflows. The challenge is not simply calling a model: each operation must remain repeatable, traceable, tenant-isolated, and safe when requests are retried or interrupted.

I architected its Portier/Worker orchestration model, strict idempotence rules, PostgreSQL Row Level Security, immutable audit trail, and Zero PII data lifecycle. The AI layer combines retrieval, structural validation, and hallucination controls to make outputs more dependable in a business setting.

`FastAPI` · `Node.js` · `PostgreSQL` · `pgvector` · `n8n` · `LLM` · `RAG`

### Chamiong

**Full Stack Engineer, Headless ERP & B2B** · November 2025–present

I lead the digital decoupling of an industrial company whose operational core remains in Odoo. The architecture separates a Next.js presentation layer and Sanity-managed content from the ERP, connecting them through resilient JSON-RPC integrations.

The public catalogue stays fast and indexable, while prices and stock remain behind authenticated access. The experience supports French, English, and Arabic—including RTL—and gives the client direct control over day-to-day content and catalogue management.

`Next.js` · `React` · `TypeScript` · `Sanity` · `Odoo` · `JSON-RPC`

### DXC Technology Morocco

**Engineering Intern, Business Intelligence & Business Applications** · July 2026–present  
*Insurance Service Line · Run teams*

I am building a management system for competency coverage in production teams. The work starts with operational data and business-rule validation, then turns that information into indicators managers can use.

It spans the competency model, data pipeline, Power BI dashboards, and the application layer that maintains source data. I focus on the full path from data entry to management decision—not a dashboard treated as an isolated deliverable.

`Power BI` · `DAX` · `Power Apps` · `Dataverse` · `Data modelling`

### Previzma

**Independent engineering project, B2B sales intelligence** · April 2026–present

ERP systems record transactions; commercial managers need signals they can interpret and act on. Previzma is my public, actively developed MVP for turning industrial B2B sales history into forecasts, operational alerts, and What-If simulations.

Its three repositories reflect deliberate ownership boundaries:

| Repository | Responsibility |
| --- | --- |
| [Spring Boot backend](https://github.com/ashurafu04/previzma-backend) | Business API, authentication, JWT/RBAC, company-scoped data access, persistence, and ML orchestration |
| [FastAPI ML service](https://github.com/ashurafu04/previzma-ml-service) | Forecasting and simulation behind an HTTP contract, separate from authentication and business persistence |
| [Angular frontend](https://github.com/ashurafu04/previzma-frontend) | The user-facing application for exploring sales data, forecasts, alerts, and scenarios |

The published MVP uses a statistical forecasting baseline by default. A trained LightGBM model is an evaluated, gated option—not a production capability I claim simply because the code supports it. The system remains under active development and hardening; its repositories document both implemented behaviour and known follow-up work.

`Java 21` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `FastAPI` · `Angular 22` · `REST`

## Other experience that shaped how I build

### General Secretariat of the Government of Morocco

**Software Engineering Intern, ERP scope with team leadership responsibilities** · July–August 2025

I contributed to an end-to-end Odoo implementation for the Direction of the Official Printing Office. The scope included business analysis, BPMN, RBAC, approval workflows, custom Python modules, PostgreSQL, documentation, and knowledge transfer across sales, subscriptions, stock, manufacturing, accounting, CRM, and HR.

That experience reinforced a principle I still use: begin with the organisation—its language, responsibilities, exceptions, and operational sequence—before designing the software around it.

### Independent consulting & product work

**Independent Consultant and Full Stack Developer** · June 2025–present

Alongside my main roles, I have delivered and explored products in different environments. **Morocco Atlas Adventure** developed my experience in multilingual delivery, SEO, deployment, and client handover. **Bnin** pushed me toward React Native, contextual AI, mobile product thinking, and local-first user experience. Earlier projects including **Cashaura** and **Listo** helped build my foundations in Java architecture, Django REST APIs, authentication, relational modelling, and collaborative delivery.

## Toolkit

| Area | Tools and practices |
| --- | --- |
| **Backend & services** | Java, Spring Boot, Python, FastAPI, Django, Node.js, Express, C#, ASP.NET Core, Laravel, REST APIs |
| **Frontend & mobile** | Angular, React, Next.js, TypeScript, React Native, Expo |
| **Data & enterprise** | PostgreSQL, Row Level Security, pgvector, Redis, Odoo, SQL Server, Oracle, MongoDB, MySQL |
| **Cloud & delivery** | AWS, Docker, GitHub Actions, CI/CD, Vercel, Netlify, k6 |
| **Architecture & applied AI** | Multi-tenant systems, distributed workflows, idempotence, RBAC, BPMN, retrieval pipelines, workflow automation, model evaluation |

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,nodejs,dotnet,angular,react,nextjs,ts,postgres,redis,docker,aws,githubactions&perline=15" alt="Selected technologies used by Achraf Malki" />
</p>

## Education & certifications

I am completing an engineering degree in **Software Engineering and Digital Systems** at **EMSI Rabat**, with graduation planned for 2027.

Selected certifications: AWS Cloud Technical Essentials, Google Agile Project Management, Meta React Native, HarvardX CS50, IBM Python, and IBM Node.js with Express.

Arabic is my native language. I work professionally in French and English.

## GitHub activity

My public repositories show only part of my engineering work; employer and client code is often private. This calendar shows the contribution activity associated with my account without exposing private repository contents.

<p align="center">
  <a href="https://github.com/ashurafu04">
    <img src="https://ghchart.rshah.org/2ea043/ashurafu04" alt="Achraf Malki GitHub contribution activity over one year" width="100%" />
  </a>
</p>

---

<div align="center">
  <h3>I like serious engineering problems, clear conversations, and products that remain useful after delivery.</h3>

  <p>
    <a href="https://achrafmalki.dev">Portfolio</a> &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/achraf-malki">LinkedIn</a> &nbsp;·&nbsp;
    <a href="mailto:achrafmalki.eng@gmail.com">Email</a>
  </p>
</div>
