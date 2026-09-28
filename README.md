<div align="center">
  <img src="./malki-achraf.png" alt="Achraf Malki logo" width="100" />

  <h1>Achraf Malki</h1>

  <p><strong>Software Engineer & IT Consultant</strong><br />
  Java / Spring Boot · Enterprise integration · Applied AI</p>

  <p>
    I design backend systems that connect business workflows, reliable data,
    and useful decision-making tools.
  </p>

  <p>
    Rabat, Morocco · EMSI engineering class of 2027 · Open to a final-year internship (PFE)
  </p>

  <p>
    <a href="https://achrafmalki.dev">Portfolio</a> ·
    <a href="https://www.linkedin.com/in/achraf-malki">LinkedIn</a> ·
    <a href="mailto:achrafmalki.eng@gmail.com">Email</a>
  </p>
</div>

---

## Featured public project

### Previzma — B2B sales intelligence

Previzma is an actively developed MVP that turns industrial sales history into management KPIs, forecasts, operational alerts, and What-If simulations.

```text
Angular 22 → Java 21 / Spring Boot 3 → PostgreSQL
                         └──────────→ FastAPI ML service
```

The Spring Boot backend owns the business domain, JWT authentication, RBAC, company scoping, persistence, and orchestration. FastAPI is a separate calculation service: its default forecast is a statistical baseline, while an offline-trained LightGBM model is used only if it passes a promotion gate. Angular presents the results without calling the database or ML service directly.

The repositories document what works, how the services interact, and what still needs hardening:

- [Spring Boot backend](https://github.com/ashurafu04/previzma-backend) — domain API, security, persistence, and ML orchestration
- [FastAPI ML service](https://github.com/ashurafu04/previzma-ml-service) — forecasting, backtesting, model comparison, and deterministic simulations
- [Angular frontend](https://github.com/ashurafu04/previzma-frontend) — dashboards, forecasts, simulations, and model-quality views

**Status:** Public MVP, not a production deployment. Integration testing and operational hardening remain in progress.

## Selected engineering work

Most client and employer code is private. These are the problems and responsibilities I can describe publicly; more context is available on my [portfolio](https://achrafmalki.dev).

### Nortis Studio · MAGMA
*Software Engineer, AI & Cloud · January 2026–present*

Architecting a multi-tenant B2B intelligence platform for concurrent AI workflows. My work focuses on the Portier/Worker orchestration model, idempotent operations, tenant isolation, auditability, and a data-minimizing lifecycle. The AI layer combines retrieval with structural validation and controls designed to make outputs more dependable.

`FastAPI` · `Node.js` · `PostgreSQL` · `pgvector` · `n8n` · `RAG`

### Chamiong
*Full-Stack Engineer, Headless ERP & B2B · November 2025–present*

Decoupling an industrial company’s customer-facing experience from its Odoo operational core. I built a Next.js presentation layer, Sanity-managed content, and JSON-RPC integrations while keeping prices and stock behind authentication. The experience supports French, English, and Arabic, including RTL layout.

`Next.js` · `React` · `TypeScript` · `Sanity` · `Odoo`

### DXC Technology Morocco
*Engineering Intern, Business Intelligence & Applications · July 2026–present*

Building a competency-coverage management system for production teams—from operational data and business rules through the data model, Power BI indicators, and the application used to maintain source records.

`Power BI` · `DAX` · `Power Apps` · `Dataverse`

Earlier, at the General Secretariat of the Government of Morocco, I contributed to an Odoo implementation spanning business analysis, BPMN, RBAC, approval workflows, custom modules, and knowledge transfer. That work reinforced a principle I still use: understand the organisation and its exceptions before designing the software boundary.

## How I approach systems

- Start with the domain, data ownership, and failure modes—not a preferred framework.
- Keep authorization and tenant isolation at the backend boundary; UI checks are for usability.
- Make engineering claims traceable through architecture notes, tests, explicit limitations, and documented decisions.

## Core toolkit

**Backend and data:** Java, Spring Boot, Spring Security, JPA, PostgreSQL, Python, FastAPI, REST APIs  
**Frontend and integration:** TypeScript, Angular, Next.js, React, Odoo, JSON-RPC  
**Delivery and applied AI:** Docker, AWS, CI/CD, retrieval workflows, model evaluation

I’m completing an engineering degree in Software Engineering and Digital Systems at EMSI Rabat, with graduation planned for 2027. I work in Arabic, French, and English.

---

<div align="center">
  <strong>Interested in a final-year internship that can grow into a long-term engineering role.</strong><br />
  <a href="mailto:achrafmalki.eng@gmail.com">Let’s talk</a> ·
  <a href="https://achrafmalki.dev">Explore my work</a>
</div>
