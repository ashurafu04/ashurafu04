<div align="center">

  <img src="./malki-achraf.png" alt="Achraf Malki" width="115" />

  <h1>Achraf Malki</h1>

  <p><strong>Software Engineer · Backend & Systems Integration</strong></p>

  <p>
    Java / Spring · Enterprise Integration · Applied AI
  </p>

  <p>
    I design backend systems, integration layers and business applications
    that connect software architecture with real operational processes.
  </p>

  <p>
    Rabat, Morocco &nbsp;·&nbsp;
    Final-year Engineering Student, EMSI Rabat &nbsp;·&nbsp;
    PFE from February 2027
  </p>

  <p>
    <a href="https://achrafmalki.dev">
      <img src="https://img.shields.io/badge/Portfolio-achrafmalki.dev-111111?style=for-the-badge" alt="Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/achraf-malki">
      <img src="https://img.shields.io/badge/LinkedIn-Achraf%20Malki-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:achrafmalki.eng@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <p>
    <a href="#public-engineering">Public engineering</a>
    &nbsp;·&nbsp;
    <a href="#professional-experience">Experience</a>
    &nbsp;·&nbsp;
    <a href="#engineering-toolkit">Toolkit</a>
  </p>

</div>

---

## Engineering activity

Most of my professional work lives in private repositories. This graph shows the development activity associated with my GitHub account without exposing employer or client code.

<p align="center">
  <a href="https://github.com/ashurafu04">
    <img src="https://ghchart.rshah.org/2ea043/ashurafu04" alt="Achraf Malki GitHub contribution activity" width="100%" />
  </a>
</p>

## Engineering approach

I work mainly at the intersection of **backend engineering, systems integration and business applications**.

I prefer to understand the operational system before choosing the technical solution: who owns the data, where information moves, what can fail, which rules must remain enforced, and which decisions the software is supposed to support. From there, I care about clear service boundaries, traceable workflows, secure access and architectures that remain understandable after the first release.

Before graduation, this approach has already taken me through four very different professional environments: a multinational IT services company, a Belgian technology studio, a national B2B industrial company and the Moroccan public sector.

Most of that engineering cannot be published. **Previzma is the public project where I expose the same approach through inspectable architecture, code and documentation.**

---

## Public engineering

### Previzma · B2B Sales Intelligence Platform

**Independent engineering project · April 2026–present**

Previzma is a public B2B platform for transforming commercial history into forecasts, operational signals and What-If simulations.

The system is deliberately separated into three components with explicit ownership boundaries rather than being built as a single application.

| Component | Responsibility |
| --- | --- |
| [Spring Boot backend](https://github.com/ashurafu04/previzma-backend) | Business API, authentication, Spring Security, JWT/RBAC, company-scoped data access, persistence and ML orchestration |
| [FastAPI ML service](https://github.com/ashurafu04/previzma-ml-service) | Forecasting, simulation, backtesting, model comparison and model-status operations |
| [Angular frontend](https://github.com/ashurafu04/previzma-frontend) | User-facing application for exploring sales data, forecasts, alerts and scenarios |

The backend owns business rules, security and persistence. The ML service remains independent behind an HTTP/JSON contract and does not own authentication or business data.

The forecasting pipeline supports feature engineering, 30/60/90-day horizons, model evaluation and backtesting through MAE, MAPE and RMSE. The published MVP serves a statistical baseline by default. A trained LightGBM model is evaluated and gated before promotion rather than being presented as production-ready simply because an artifact exists.

`Java 21` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `Angular` · `Python` · `FastAPI` · `LightGBM` · `REST`

---

## Professional experience

### Nortis Studio · MAGMA

**Software Engineer, AI & Cloud** · January 2026–present · Belgium, remote

MAGMA is a multi-tenant B2B intelligence platform where concurrent AI workflows need to remain traceable, isolated and safe under retries and failures.

I worked on its backend and orchestration architecture, including workflow coordination, idempotence, PostgreSQL Row Level Security, auditability and controlled data lifecycles. The AI layer combines retrieval, structured processing and validation mechanisms to make model outputs more dependable in business workflows.

`FastAPI` · `Node.js` · `PostgreSQL` · `pgvector` · `n8n` · `LLM/RAG`

### Chamiong

**Full Stack Software Engineer, Headless ERP Integration** · November 2025–present · Rabat, remote

I work on the digital decoupling of an industrial B2B company whose operational core remains in Odoo.

The architecture separates the web experience and content layer from the ERP through resilient JSON-RPC integrations and an adaptation layer. Public catalogue content remains independently manageable while operational data such as authenticated pricing and stock continues to come from the ERP.

`Next.js` · `React` · `TypeScript` · `Sanity` · `Odoo 17` · `JSON-RPC`

### DXC Technology Morocco

**Engineering Intern, Business Intelligence & Business Applications** · July 2026–September 2026  
*Insurance Service Line · RUN*

I worked on a competency-management and reporting solution for Insurance RUN teams, starting from operational data and business rules and carrying them through to management indicators and an application layer for maintaining source information.

The work also involved production reporting systems, data-quality analysis, reverse engineering, anomaly investigation, root-cause analysis and technical documentation.

`Power BI` · `DAX` · `Power Apps` · `Dataverse` · `Data Modelling`

### General Secretariat of the Government of Morocco

**Software Engineering Intern, ERP** · July–August 2025

I contributed to an end-to-end Odoo implementation for the Direction of the Official Printing Office across sales, subscriptions, purchasing, inventory, manufacturing, accounting, CRM and HR.

The work covered business analysis, gap analysis, BPMN, RBAC, approval workflows, custom development, data migration, specifications, documentation and knowledge transfer.

That experience established a principle I still use today: **understand the organisation first, then design the software around it.**

`Odoo 17` · `Python` · `PostgreSQL` · `BPMN` · `RBAC`

---

## Selected product & consulting work

Alongside my main roles, I have built and delivered products in different technical and business environments.

**Morocco Atlas Adventure** gave me end-to-end experience with a multilingual production web product, SEO, deployment, domain configuration and client handover.

**Cashaura** helped establish my foundations in Java application architecture, relational data modelling, authentication, transactions and layered application design.

Other product experiments have taken me through mobile development, contextual AI, REST APIs and collaborative delivery. I use these projects primarily as environments for learning engineering decisions rather than collecting technologies.

---

## Engineering toolkit

| Area | Core technologies & practices |
| --- | --- |
| **Backend** | Java, Spring Boot, Python, FastAPI, Node.js, Express, PHP/Laravel, REST APIs |
| **Frontend** | Angular, React, Next.js, TypeScript |
| **Data & enterprise** | PostgreSQL, SQL, Redis, pgvector, Odoo, SQL Server, Oracle, MySQL |
| **Delivery** | Docker, Git/GitHub, GitHub Actions, CI/CD, Linux, AWS |
| **Architecture** | Systems integration, API boundaries, multi-tenancy, RBAC, idempotence, BPMN |
| **Applied AI** | LLM/RAG, embeddings, retrieval pipelines, workflow automation, model evaluation |

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=java,spring,python,fastapi,nodejs,angular,react,nextjs,ts,postgres,redis,docker,aws,githubactions&perline=14"
    alt="Selected technologies used by Achraf Malki"
  />
</p>

---

## Education & certifications

**Engineering Degree in Computer Science & Networks**  
EMSI Rabat · Digital Development & Information Systems specialization · 2022–2027

Selected certifications:

`Oracle Certified Professional: Java SE 17 Developer` ·
`AWS Cloud Technical Essentials` ·
`HarvardX CS50 & SQL` ·
`Google Agile Project Management`

Arabic is my native language. I work professionally in French and English.

---

<div align="center">

  <h3>Engineering systems that remain clear, reliable and useful after delivery.</h3>

  <p>
    Open to a 6-month PFE from February 2027 with the objective of long-term professional continuity.
  </p>

  <p>
    <a href="https://achrafmalki.dev">Portfolio</a>
    &nbsp;·&nbsp;
    <a href="https://www.linkedin.com/in/achraf-malki">LinkedIn</a>
    &nbsp;·&nbsp;
    <a href="mailto:achrafmalki.eng@gmail.com">Email</a>
  </p>

</div>
