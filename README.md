<h1 align="center">Achala Arunalu - AI Product Management and Delivery Governance</h1>

<p align="center">
  <b>Stablecoin Banking and Fintech, <a href="https://stablepeg.org/">Stablepeg.org</a></b><br>
  <b>Sustainability tech., <a href="https://susdevos.org/">Susdevos.org</a></b><br>
  <b>Real Estate tech., <a href="https://liveinlanka.com/">Liveinlanka.com</a></b><br>
  <sub>Stablecoin banking - cards, crypto, fiat rails, Multi-tenant SaaS, carbon accounting, and civic platforms — Agile [AI] Product lead, architecture through go live and maintenance.</sub>
</p>

<p align="center">·
  <a href="{{https://www.linkedin.com/in/achala-arunalu-meddegama/}}">LinkedIn</a> ·
  <a href="mailto:{{PUBLIC_EMAIL}}">Email</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" alt="Astro">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white" alt="OpenAPI">
</p>

---

I run **[Software Lifecycle Consultants](https://github.com/Software-Lifecycle-Consultants)**, where we
take products from architecture to production — and publish most of the result under open licences.

My current focus is **[SusDevOS](https://github.com/Software-Lifecycle-Consultants/SusDevOS-Pro)**: a
multi-tenant SaaS platform for greenhouse-gas reporting and sustainable development management. It's
the place where the two halves of my work meet — I've spent years on environmental organising, and
this is that concern expressed as an auditable system rather than a campaign.

The through-line everywhere else is **software that outlives the person who built it**: tri-lingual
government tooling maintained by volunteers, hotel operations handed to non-technical staff, internal
templates that make the next build cheaper than the last. Documented setup, honest schemas, real
auth, containerised deploys, and tests that mean something.

15+ years in Singapore and Sri Lanka. Currently open to Stable coin banking and fintech product/ program roles.

---

### Selected work

| Project | What it does | Stack |
|---|---|---|
| **[SusDevOS-Pro](https://github.com/Software-Lifecycle-Consultants/SusDevOS-Pro)** | Multi-tenant GHG reporting and ecosystem-tracking SaaS for property and infrastructure. Server-side emissions engine, Scope 2 location- *and* market-based methods, verification locks that make audited records immutable, row-level tenant isolation, RBAC across 13 modules. **219 pytest tests.** | Django 5.1, Postgres 16, Redis 7, Celery, Next.js 14, TypeScript |
| **[slc-open-hms](https://github.com/Software-Lifecycle-Consultants/slc-open-hms)** | Open-source hotel management platform — reservations, room inventory, guest services, payments, real-time status. **511 commits**, MIT, 3★ / 2 forks. | Next.js, TypeScript, MUI, Leaflet |
| **[doa-farm-ops](https://github.com/Software-Lifecycle-Consultants/doa-farm-ops)** | Cost-of-cultivation reporting for Sri Lanka's Department of Agriculture. Farmers and field officers log land, crops and costs. Sinhala / Tamil / English throughout, with map-based land marking. **665 commits.** | Next.js, Express, Redux Toolkit, i18next, OpenLayers |
| **[cycleparadise](https://github.com/Software-Lifecycle-Consultants/cycleparadise)** | Cycling-tour booking platform — calendar bookings, accommodation management, admin dashboard, SEO-first static generation. | Astro 4.16 hybrid, TS strict, Prisma, Docker multi-stage |
| **[reforestsrilanka.com](https://github.com/achala87/reforestsrilanka.com)** | Released so any environmental org could fork it and stand up their own site. **4 forks** — it got reused, which was the point. | PHP, JS |

<sub>More at **[@Software-Lifecycle-Consultants](https://github.com/Software-Lifecycle-Consultants)** —
a .NET API backend, Shopify themes, Python MVPs, and a public proof-of-concept archive.</sub>

---

### What I actually bring

- **Domain-heavy backend design.** GHG accounting isn't CRUD: dual-method Scope 2, verification
  states that must refuse writes, and a calculation engine that has to survive an auditor. I model
  that server-side, on purpose, and test it — 219 tests on SusDevOS alone.
- **Multi-tenancy done properly.** Row-level isolation by entity, JWT with short-lived access
  tokens, role-based access across 13 modules, feature gating per tenant.
- **Contract-first APIs.** OpenAPI schema via drf-spectacular, TypeScript client generated from it.
  The frontend can't drift from the backend because it isn't hand-written.
- **Polyglot by choice, not accident.** Django and .NET and Express and Laravel on the back;
  Next.js and Astro on the front; Postgres underneath. I pick per problem and can defend the pick.
- **Internationalisation designed in, not bolted on.** Sinhala/Tamil/English schemas, geospatial
  land marking, hierarchical geographies with radius search.
- **Delivery for low-budget, high-stakes users.** Government agriculture, environmental NGOs, small
  tour operators. No SRE team, no rescue budget — it has to work and keep working.

---

### Open to
- **Senior / lead product and technical roles** — remote or in Dubai/ UAE, Singapore, Sri Lanka, Berline, Germany.
- **Consulting engagements** — product and innovation, road mapping, release governance and delivery operating systems setup, greenfield builds, architecture 

---

<details>
<summary><b>GitHub activity</b></summary>
<br>

<img src="https://github-readme-stats.vercel.app/api?username=achala87&show_icons=true&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=achala87&layout=compact&hide_border=true&langs_count=8" alt="Top languages">

</details>

<p align="center"><sub>
Open source as a delivery model — if something here is useful to your organisation, take it and run.
</sub></p>
