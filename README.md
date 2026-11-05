# Hi, I'm Ibrahim 👋

**Software Developer · Full-Stack Developer · AI Enthusiast** in Doha, Qatar 🇶🇦\
BSc Information Systems, **University of Doha for Science & Technology (UDST)**, May 2026

I build web applications end to end, from Python and PostgreSQL backends to React and JavaScript frontends, and I add AI where it solves a real problem. In my AI work the model understands the user, while prices, stock and approvals come from tested code. I back my work with tests and evaluation results, and I write down what still fails.

- 🌱 Currently on the **CertiMinds Launchpad pathway**, building AI applications with senior mentoring
- 💼 Previously at **Alfardan Properties**, where I built the foundations of an internal payment workflow app and worked on Docker, Linux and API integration
- 🗣️ Arabic · English

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/REST_APIs-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="REST APIs">
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API">
  <img src="https://img.shields.io/badge/AI%2FML-RAG_%C2%B7_LoRA-6E40C9?style=flat-square" alt="AI/ML">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
</p>

---

## 💼 Experience

### IT Support Intern · Alfardan Properties, Doha · Apr – Jun 2026

My title was IT Support, but most of my work was software development, alongside infrastructure and support.

**Payment Register web application** (internal, private repository)\
Built the foundations of an internal app to move payment registration, tracking and approval into one system.
- Designed a modular Flask backend with separate modules for users, payments, approvals, reporting and master data
- Set up the PostgreSQL 15 data models and migrations with SQLAlchemy and Flask-Migrate
- Built the first dashboard (Chart.js) and the payment creation form, with login and validated forms
- Planned the next stages: vendor records, cost centres, attachments, approval workflows, Excel export and Azure AD single sign-on

`Python` `Flask` `PostgreSQL` `SQLAlchemy` `Flask-Login` `Jinja2` `Bootstrap 5` `JavaScript` `Chart.js`

**Infrastructure, integration and support**
- Recovered a broken WordPress website and rebuilt it as a static HTML/CSS/JavaScript site that keeps its content
- Ran self-hosted document and e-signature tools (DocuSeal, OpenSign, Stirling-PDF) with Docker Compose behind Caddy
- Tested APIs in Postman with Okta OAuth 2.0 machine-to-machine (`client_credentials`) tokens
- Worked on Power Apps business apps for asset management and petty cash
- Reinstalled and configured Ubuntu, and handled hardware and software support

`Docker` `Docker Compose` `Caddy` `Linux` `Postman` `OAuth 2.0` `Okta` `Power Apps` `SharePoint`

---

## ⭐ Featured projects

### [Ceramica Nova AI: Sales Consultant](https://github.com/IbrahimElhomsany/certiminds-ai-assessment) · CertiMinds project, 2026

An AI sales assistant for a tiles company. It finds out what the customer needs, recommends tiles and bathroom sets, calculates quantities, checks stock and produces a PDF quotation in QAR. The LLM never decides a price, a quantity or an approval.

- Claude tool-use agent calling deterministic tools (recommend, quantity, inventory, quote), with a rule-based fallback when the LLM is unavailable
- LLM gateway with timeouts, retries, provider fallback, caching, rate limiting and metrics
- Hybrid search (BM25 + embeddings) with citations; documents containing injected instructions are quarantined
- Guardrails in code: every price in a reply must come from a tool or the catalog
- Fine-tuned a small model (Qwen2.5-0.5B, LoRA on Apple MLX): overall score **0.46 → 0.98** on 45 held-out cases
- **73 tests** passing; evaluation **36/36** offline and **36/38** with the Claude agent, with the 2 failures explained

`Python` `FastAPI` `Claude API` `Pydantic` `RAG` `LoRA` `MLX` `pytest` `HTML/CSS/JS`

### [CertiMinds AI Chatbot](https://github.com/IbrahimElhomsany/certiminds-ai-chatbot)

A chatbot that answers questions about CertiMinds using only the company website, with links to its sources. When the answer isn't on the site, it says so instead of guessing.

- Semantic search over 121 website sections with a local embedding model, no vector database needed
- Compared 5 embedding models and improved chunking based on the results: held-out retrieval **68% → 92%**
- Claude returns structured output saying whether the site answers the question and which sections it used
- React chat interface with sources, copy button, status indicator, retry and screen-reader labels; 22 tests

`Python` `Flask` `React` `Vite` `Claude API` `sentence-transformers` `REST API` `pytest`

---

## 🛠️ Skills

| Area | Tools |
| --- | --- |
| Backend | Python, Flask, FastAPI, REST APIs, SQLAlchemy, Pydantic |
| Databases | PostgreSQL, SQL |
| Frontend | React, JavaScript, HTML, CSS, Bootstrap, Jinja2 |
| AI / ML | Claude API, tool-use agents, RAG, embeddings, LoRA fine-tuning, evaluation |
| DevOps & infra | Docker, Docker Compose, Caddy, Linux (Ubuntu), Git |
| Integration & testing | Postman, OAuth 2.0, Okta, pytest |
| Business apps | Microsoft Power Apps, SharePoint |

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ibrahim-elhomsany-039236362/) · ✉️ [ibrahimhomsany1@gmail.com](mailto:ibrahimhomsany1@gmail.com) · ✉️ [ibrahim.e@certiminds.com](mailto:ibrahim.e@certiminds.com)
