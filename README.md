<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:2c5364,100:0f2027&height=250&section=header&text=Siddharth%20Ahir&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=AI%20Engineer%20building%20systems%20that%20can%20prove%20themselves&descAlignY=55&descAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&pause=1200&color=6FE0FF&center=true&vCenter=true&width=700&lines=Building+LLM+systems+that+show+their+work;RAG+that+cites+real+sources%2C+not+guesses;Multi-agent+pipelines+with+a+human+in+the+loop;Currently%3A+MSc+Data+Science%2C+Berlin" alt="Typing SVG" />

<br/>

<a href="mailto:sidahir25820@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://sid-portfolio.lovable.app/">
<img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/siddharth-ahir-798754262/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<img src="https://komarev.com/ghpvc/?username=sidddharthhahir&label=Profile+Views&color=6FE0FF&style=flat" />

</div>

<br/>

## 📖 The origin story

I used to think AI engineering meant getting a model to say something clever.

Then I got a job where an LLM call went into production, and three questions showed up that no amount of prompt tweaking could answer: **what did that just cost us? how long did it actually take? and can we prove the answer wasn't made up?**

Nobody had built for those questions. So I did.

That's still the job, six months and a handful of side projects later — building AI systems that don't just work, but can explain themselves when someone asks how.

<br/>

## 🔬 How I actually work

```diff
+ If something annoys me personally, it usually becomes a project
+ I don't trust a number I can't see — dashboards before optimisation, always
+ Reading someone else's source beats reading their documentation
- A clever abstraction nobody can explain in one sentence — deleted, no eulogy
+ Week one: mostly questions. Week two: actually useful.
```

<br/>

## 💼 The Firmway chapter — *Mar 2026 to Aug 2026*

<img src="https://img.shields.io/badge/Status-Completed-lightgrey?style=flat-square"/>

Six months at a Frankfurt-based supply chain intelligence company. Here's what actually happened:

<table>
<tr>
<td width="50%" valign="top">

**The hidden bottleneck**

Wired distributed tracing across 8 microservices, mostly to stop guessing where our AI pipeline was slow. The traces surfaced one single external API call responsible for the vast majority of total request time. Nobody had suspected it. The data did the arguing for me.

</td>
<td width="50%" valign="top">

**The cost tracker that lied twice**

Built a real-time system to track what every LLM call actually cost us. It broke silently, twice — once under-reporting output tokens, once about to miscount spend by a third after a pricing change. I caught both. Small catches. Real money.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**The search infrastructure**

Built the embedding and semantic-search layer that let retrieval run on actual similarity instead of keyword luck — the invisible plumbing behind every "smart" answer the system gave.

</td>
<td width="50%" valign="top">

**The refactor nobody asked for**

Found a legacy module held together by branching logic and switch statements. Rebuilt it into a typed, extensible pattern, fully tested. Nobody noticed. That was the point.

</td>
</tr>
</table>

<br/>

## 🛠️ What's actually in the toolbox

<p align="center">
<img src="https://skillicons.dev/icons?i=python,java,django,fastapi,nodejs,react,nextjs,ts,tailwind,postgres,mysql,docker&perline=6" alt="Skills"/>
</p>

<div align="center">

`LLM Integration` `RAG Pipelines` `Semantic Search` `Claude` `Ollama` `OpenTelemetry` `Langfuse`

</div>

<br/>

## 🚀 Things I built because I wanted them to exist

<br/>

<table>
<tr>
<td width="50%">

### 📖 Madhav
**A RAG system with a conscience**

Ask it anything about the Bhagavad Gita. It'll answer — but only if it can point to the exact verse the answer came from. If the citation doesn't check out against the real text, the answer never reaches you. No hallucinated scripture, ever.

`Python` `FastAPI` `Embeddings` `Hybrid Search`

[**→ See the repo**](https://github.com/sidddharthhahir/madhav)

</td>
<td width="50%">

### ⚡ Pulse
**Five AI agents, one human veto**

A researcher agent finds topics. A ranker agent picks the good ones. A writer agent drafts them in my voice. Nothing publishes until I say yes — and every post's real performance flows back in, so next week's ranking is smarter than this week's.

`Python` `Multi-agent orchestration` `LLM APIs`

[**→ See the repo**](https://github.com/sidddharthhahir/Pulse-)

</td>
</tr>
<tr>
<td width="50%">

### 🧭 Startup Intelligence Agent
**The AI that told me my idea needed work**

I fed it my own startup idea to test it. It scored it 6 out of 10, told me exactly why, and suggested a sharper angle. Three reasoning passes — market, competition, feasibility — end in a go-to-market plan and a deployable landing page, same session.

`Next.js` `PostgreSQL` `TypeScript` `Structured LLM output`

[**→ See the repo**](https://github.com/sidddharthhahir/startup-intelligence-agent)

</td>
<td width="50%">

### 🎬 MovieWise XAI
**A recommender that shows its work**

*Master's thesis · graded 1.3 (94/100)*

Every movie suggestion arrives with a plain-language reason, generated locally from the exact evidence that produced the ranking. No black box. No external API. No data ever leaves the machine.

`Python` `LightFM` `TF-IDF` `Ollama` `Streamlit`

[**→ See the repo**](https://github.com/sidddharthhahir/MovieWise-XAI)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="100%">

### 📄 AI Resume Customizer
**The tool that's writing this bio's résumé too**

Built out of pure frustration with rewriting my resume for every single application. Feed it a job description — it adjusts emphasis and phrasing to match, and refuses point-blank to invent a skill you don't have. Tracks every application. Exports clean PDF/DOCX. This is, genuinely, the tool behind the resume that got me my last role.

`React` `Node.js` `MySQL` `LLM APIs`

[**→ See the repo**](https://github.com/sidddharthhahir/ai-resume-customizer)

</td>
</tr>
</table>

<br/>

## 🗺️ Where this goes next

```
2026 ─── Staying in the unglamorous parts: cost, latency, correctness.
          That's where systems actually break — not in the demo.
                    │
                    ▼
2027 ─── Moving from "does it work" to "can I prove it works."
          Evaluation that reflects real usage. Retrieval that survives
          messy input. Agents that fail gracefully, not silently.
```

<br/>

## 📊 The receipts

<p align="center">
<img src="https://raw.githubusercontent.com/sidddharthhahir/sidddharthhahir/main/github-contribution-grid-snake.svg" alt="Snake animation"/>
</p>

<p align="center">
<img src="https://github-stats-extended.vercel.app/api?username=sidddharthhahir&show_icons=true&theme=tokyonight&hide_border=true" height="165" alt="GitHub Stats"/>
<img src="https://streak-stats.demolab.com/?user=sidddharthhahir&theme=tokyonight&hide_border=true" height="165" alt="Streak Stats"/>
</p>

<p align="center">
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=sidddharthhahir&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>
</p>

<br/>

## 🎓 The paper trail

| | | |
|---|---|---|
| 🎓 | **MSc Data Science** | Arden University, Berlin · May 2026 – Present |
| 🎓 | **MSc Computer Science** *(transferred)* | IU International University of Applied Sciences · Sep 2023 – May 2026 · Thesis graded 1.3 (94/100) |
| 🎓 | **Bachelor of Computer Application** | Gujarat University, India · Jul 2019 – Apr 2022 |

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:2c5364,100:0f2027&height=150&section=footer&animation=twinkling"/>

**Still reading? Then you're exactly who I want to talk to.**

</div>
