<h1 align="center">Hi there, I'm Michael Oluwamayowa Akindiilete 👋</h1>

<h3 align="center">Senior Frontend Engineer • Fintech • AI Workflow Orchestration</h3>

<p align="center">
  <a href="https://uiforge.com.ng"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:michael.akindiilete@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/michael-akindiilete/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://komarev.com/ghpvc/?username=makindiilete&style=for-the-badge&color=blueviolet" alt="Profile views"/>
</p>

---

### 🚀 About Me

- 🏦 **Senior Frontend Engineer** with **7+ years** building scalable production systems for fintech (React, React Native, Next.js, Angular)
- 🤖 Architect of **Advancly Bank Statement Analysis** — a multi-model Claude pipeline that reconciles bank statements at scale and automates credit decisioning
- 🧰 Creator of **Lintlore** — turns code-review history into rules your AI coding agents obey, across GitHub, GitLab & Azure Repos
- 🧩 Lead engineer on micro-frontend migrations, design systems, and CBN-compliant KYC at **Moniepoint** and **Advancly**
- 🛠️ Currently extending into platform-level **AI workflow orchestration**: Python services, multi-LLM routing, and developer tooling that lifts entire teams
- 📍 Based in **Lagos, Nigeria** • 🗣️ English & Yoruba

---

### 🛠️ Tech Stack

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

**Backend & AI**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_SDK-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### ⭐ Featured Projects

#### 🧰 [Lintlore](https://github.com/makindiilete/lintlore) — *turn code review into rules your AI agents obey*

A developer-productivity engine that mines code-review comments on your merge/pull requests, distills recurring feedback into reusable engineering rules, and forces every supported AI coding agent (Claude Code, Cursor, GitHub Copilot, Factory Droid, Kilo Code, and any `AGENTS.md`-aware agent) to consult and validate against them — so the same correction is never given twice.

- 🔁 **Two input streams, one rulebase** — continuous MR-comment mining *plus* one-shot Confluence standards seeding.
- 🛡️ **Defense in depth** — four enforcement layers (skills Step 0, pre-commit hook, Cursor MDC, per-rule-file pointers) that block commits on blocker-severity violations.
- 🔌 **Platform-agnostic pipeline** — GitLab adapter shipped; GitHub & Azure Repos on the roadmap behind the same normalized interface.
- ⚙️ Node ≥22 · LLM-powered (Claude by default, swappable) · MIT-licensed, no telemetry, no lock-in.

#### 🏦 Advancly Bank Statement Analysis — *multi-model AI credit pipeline*

End-to-end **Python (FastAPI) + Claude AI** service that converts borrower bank statements between PDF, Excel, and JSON in any direction — and, when output is Excel, automatically runs an AI credit analysis the team can act on in minutes.

- 🔁 **Six conversion paths** between PDF, Excel, and JSON; source bank auto-detected, outputs branded in that bank's actual colors.
- 📊 **AI credit decisioning** in the Excel output: risk rating, red/green flags, income-pattern summary, loan recommendation.
- ⚙️ **Chunked multi-model pipeline with a mathematical reconciliation gate** — cut a 1,321-page statement (14,358 transactions) from 2+ hours to **~20 minutes at 0.0 kobo difference**.
- 💼 **Business impact:** replaced a workflow that needed ~10 analysts; now runs with 3–5 supervisors verifying AI recommendations.

---

### 📊 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=makindiilete&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide=stars"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=makindiilete&layout=compact&theme=tokyonight"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=makindiilete&theme=tokyonight" alt="GitHub Streak"/>
</p>

---

### 📫 Let's Connect

I'm open to senior frontend, fullstack, and AI-engineering opportunities. Reach me at **michael.akindiilete@gmail.com** or via my [portfolio](https://uiforge.com.ng).
