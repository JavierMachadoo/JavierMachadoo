<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0077B5,100:25D366&height=180&section=header&text=Javier%20Machado&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Software%20Developer%20%C2%B7%20Automation&descAlignY=55&descSize=16" alt="Javier Machado" />

<a href="https://www.linkedin.com/in/javiermachadoo/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:javiermachado245@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>

---

## About

Advanced Systems student from Uruguay, focused on building software that real
businesses actually run on. Most of my work replaces manual, spreadsheet-driven
processes with centralized web platforms: bookings, tournaments, workshop jobs,
sales pipelines.

- Building multi-tenant SaaS platforms end to end, from data model to deployment.
- Automating operational processes that used to live in WhatsApp and spreadsheets.
- Applying modern AI to data analysis, conversation practice, and decision support.
- Comfortable across the stack: TypeScript and Python for product, C# and Java from formal training.

---

## Stack

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,py,cs,java,html,css&theme=dark" height="42" alt="TypeScript, JavaScript, Python, C#, Java, HTML, CSS" />

**Frameworks & runtime**

<img src="https://skillicons.dev/icons?i=react,angular,nodejs,tailwind,dotnet&theme=dark" height="42" alt="React, Angular, Node.js, Tailwind, .NET" />

**Data & infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,supabase,mysql,docker,git,github&theme=dark" height="42" alt="PostgreSQL, Supabase, MySQL, Docker, Git, GitHub" />

---

## Selected work

Most of these repositories are private (client work and university coursework), so
the links are listed for reference rather than browsing. Where a public deployment
exists, it is linked directly.

### Own projects

| Project | What it does | Stack | Repo |
| --- | --- | --- | --- |
| **LagomarPadelClub** — [live app](https://torneos.lagomarpadelclub.uy/) | Tournament management for a padel club. Its core is a grouping algorithm that cross-references every pair's time-slot availability and forms optimal three-pair groups — exhaustive search with pruning for small sets, greedy selection beyond that — then drives the full lifecycle: registration with partner invitations, group standings, seeded knockout bracket, and permanent archiving. | Python 3.13 · Flask 3 · Supabase (PostgreSQL) · Jinja2 · Bootstrap 5 | 🔒 Private · live in production |
| **Sales-Sparring-AI** | Multi-tenant sales-training simulator. Reps rehearse against four AI buyer personalities — hostile, hesitant, technical, impulsive — in a streaming chat, then receive automatic scored feedback. Includes a per-company dashboard and full conversation history. | React 18 · TypeScript · Vite · Tailwind · Zustand · FastAPI · Google Gemini · Supabase | 🔒 Private |
| **Taller-LevaTech** | Storefront for a workshop specialised in programmable car ECUs. Customers filter the catalogue by category, brand, price and stock, build a cart, and send the order straight to WhatsApp — no signup, no online payment. | React 19 · TypeScript · Vite · Tailwind · Zustand · React Hook Form · Zod | 🔒 Private |
| **Alquimia Marketing** — [live site](https://javiermachadoo.github.io/marketing-landing-Alquimia/) | Conversion-oriented landing page for a digital marketing consultancy: services, testimonials, client portfolio, and a floating WhatsApp/email contact. Scroll-reveal animation via the Intersection Observer API, zero runtime dependencies. | HTML5 · CSS3 · Vanilla JS · SVG | 🔒 Private · live on GitHub Pages |

### University projects (Universidad ORT Uruguay)

Coursework for *Diseño de Aplicaciones*, built in three-person teams under a formal
delivery process: layered architecture, a unit-test project per layer, code review,
and defended deliverables.

| Course | Project | What it does | Stack | Repo |
| --- | --- | --- | --- | --- |
| **Diseño de Aplicaciones 1** | NearDupFinder | Detects near-duplicate records across CSV datasets. Solution split into Domain, Services, DataAccess, DTOs and Utilities, each with its own dedicated test project, behind a Blazor interface. | C# · .NET · Blazor · Docker | 🔒 Private |
| **Diseño de Aplicaciones 2** | DarkKitchen | Management system for a dark kitchen. Clean-architecture solution separating abstractions, domain, business logic, data access, mapping and contracts, with a service factory for dependency injection, pluggable JSON and XML importers, a REST Web API, and an Angular front end. | C# · .NET · ASP.NET Web API · Angular · TypeScript · Docker | 🔒 Private |
---

## GitHub stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=JavierMachadoo&hide_border=true&background=transparent&ring=0077B5&fire=25D366&currStreakLabel=0077B5" alt="Streak" />

</div>

---

## Contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JavierMachadoo/JavierMachadoo/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JavierMachadoo/JavierMachadoo/output/pacman-contribution-graph.svg">
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/JavierMachadoo/JavierMachadoo/output/pacman-contribution-graph.svg">
</picture>

</div>

---

## How I work with AI agents

I don't use AI as autocomplete. I run a harness around it: a spec-driven pipeline,
bounded sub-agents, persistent memory, and adversarial review before anything merges.
The human leads and the agent executes, and that only works when the contract is
written down first.

| Layer | What it does |
| --- | --- |
| **Spec-Driven Development** | Every change walks a pipeline: explore, propose, spec, design, tasks, apply, verify, archive. No code is written until the requirements and the design are on disk and approved. |
| **Orchestrator + bounded workers** | The main thread coordinates and never implements. Exploration, writing, and verification each go to a narrow sub-agent with a scoped brief, so the parent context stays thin and the reasoning stays traceable. |
| **Persistent memory** | Decisions, conventions, and root causes are saved across sessions, so a context reset doesn't erase the reasoning behind an architecture. |
| **Adversarial dual review** | Two blind reviewers grade the same diff independently, then a synthesis pass applies only the fixes both agree on. Disagreement means the change isn't ready. |
| **Reusable skills** | Recurring workflows (commit style, PR slicing, doc design, issue triage) are packaged as instruction modules instead of being re-explained every session. |
---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:25D366,100:0077B5&height=120&section=footer" alt="" />

</div>
