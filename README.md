<!-- Animated Banner -->
<div align="center">

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=220&section=header&text=Siddharth%20Ahir&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%20Applications%20%7C%20Intelligent%20Systems&descAlignY=55&descAlign=50"/>
</p>

<h2 align="center">AI Engineer | LLM Applications • RAG Systems • Multi-Agent Pipelines</h2>

<p align="center">
Berlin, Germany
</p>

<p align="center">
<a href="mailto:sidahir25820@gmail.com">Email</a> •
<a href="https://sid-portfolio.lovable.app/">Portfolio</a> •
<a href="https://www.linkedin.com/in/siddharth-ahir-798754262/">LinkedIn</a>
</p>

<p align="center">
<b>Most of my code exists to answer one question: can you prove it?</b>
</p>

</div>

---

# 👤 About Me

I moved into AI from full-stack development, and the assumption I brought with me was wrong. I thought the hard part would be getting a model to give a good answer. It isn't. The hard part is knowing why it gave that answer, what it cost you to get it, and whether you can trust it enough to ship.

That's the gap most of my work sits in now — not making AI smarter, but making it accountable.

Currently pursuing an **MSc in Data Science (Arden University, Berlin)**. Previously MSc Computer Science at IU International University of Applied Sciences, transferred to go deeper into the maths I was taking on faith.

---

# 🧠 Working Habits

* If something annoys me enough personally, it usually becomes a project
* I don't trust a number I can't see — dashboards before optimisation, always
* Reading someone else's source beats reading their documentation
* A clever abstraction that nobody can explain in one sentence gets deleted
* First week: mostly questions. Second week: actually useful

---

# 💼 Currently / Recently — Firmway GmbH, AI Engineer (Working Student)

* Instrumented **8 microservices with distributed tracing** — the exercise itself surfaced a single external API call responsible for 88% of total request latency
* Designed and shipped **per-call LLM cost accounting** — caught two separate cases where the system was silently under-reporting real spend
* Built **embedding and semantic-search infrastructure** so retrieval decisions are based on actual similarity, not keyword luck
* Rebuilt a legacy evidence-handling module into a typed, extensible structure — replaced branching logic with a pattern that's fully covered by tests

---

# 👨‍💻 Technologies

### AI / LLM

<p>
<img src="https://img.shields.io/badge/Python-AI-blue?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/LLM-Integration-purple"/>
<img src="https://img.shields.io/badge/RAG-Pipelines-green"/>
<img src="https://img.shields.io/badge/Semantic%20Search-orange"/>
<img src="https://img.shields.io/badge/Claude-D97757"/>
<img src="https://img.shields.io/badge/Ollama-000000"/>
</p>

### Backend

<p>
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white"/>
</p>

### Frontend

<p>
<img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white"/>
</p>

### Data & Observability

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7"/>
<img src="https://img.shields.io/badge/Langfuse-black"/>
</p>

---

# 🚀 Featured Projects

### 📖 Madhav

An answer-engine over the Bhagavad Gita that won't cite a verse it can't produce. It runs both keyword and embedding-based retrieval, then checks every citation against the actual source text before letting an answer through — if the verse doesn't exist, neither does the answer.

**Stack:** Python · FastAPI · Embeddings · Hybrid Search

🔗 https://github.com/sidddharthhahir/madhav

---

### ⚡ Pulse

An assembly line of AI agents for LinkedIn content — one researches, one ranks the ideas, one writes, all coordinated in sequence. Nothing goes out the door without me approving it first, and every post's real performance gets fed back in so the ranking gets sharper over time.

**Stack:** Python · Multi-agent orchestration · LLM APIs

🔗 https://github.com/sidddharthhahir/Pulse-

---

### 🧭 Startup Intelligence Agent

Describe a startup idea and get back something closer to a VC memo than a compliment. Three separate analysis passes — market sizing, competitive landscape, feasibility — each forced into a strict schema, ending in a go-to-market plan and a working landing page, same session.

**Stack:** Next.js · PostgreSQL · TypeScript · Structured LLM output

🔗 https://github.com/sidddharthhahir/startup-intelligence-agent

---

### 🎬 MovieWise XAI — Master's Thesis (1.3 / 94 out of 100)

Recommendation systems are usually black boxes; this one has to show its reasoning. Every suggestion comes with a plain-language explanation, generated locally from the same evidence that produced the ranking — nothing sent externally, nothing hidden.

**Stack:** Python · LightFM · TF-IDF · Local LLM (Ollama) · Streamlit

🔗 https://github.com/sidddharthhahir/MovieWise-XAI

---

### 📄 AI Resume Customizer

Built this out of frustration with rewriting my own resume for every application. It reads a job description, adjusts emphasis and phrasing to match, and refuses to invent skills you don't have. Also tracks applications and exports clean PDF/DOCX. This is, genuinely, the tool behind the resume that got me my current role.

**Stack:** React · Node.js · MySQL · LLM APIs

🔗 https://github.com/sidddharthhahir/ai-resume-customizer

---

# 🎯 Roadmap

**2026 (now):** Staying in the unglamorous parts of AI engineering — cost, latency, and correctness — because that's where systems actually break in production, not in a demo.

**2027:** Moving from "does it work" to "can I prove it works" — building evaluation that reflects real usage, retrieval that survives messy inputs, and agent chains that fail gracefully instead of silently.

---

# 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/sidddharthhahir/sidddharthhahir/main/github-contribution-grid-snake.svg" />
</p>

---

# 🎓 Education

**MSc Data Science** — Arden University, Berlin *(May 2026 – Present)*

**MSc Computer Science** — IU International University of Applied Sciences, Berlin *(Sep 2023 – May 2026, transferred)*
Thesis: MovieWise XAI — graded 1.3 (94/100)

**Bachelor of Computer Application** — Gujarat University, India *(Jul 2019 – Apr 2022)*

---

# 📬 Let's Connect

📧 [sidahir25820@gmail.com](mailto:sidahir25820@gmail.com)

🌐 https://sid-portfolio.lovable.app

💼 https://www.linkedin.com/in/siddharth-ahir-798754262

<div align="center">

*Ask me about the day I found out one API call was eating 88% of our request time.*

</div>
