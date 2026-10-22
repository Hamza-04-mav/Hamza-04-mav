<!-- ╔══════════════════════ HEADER ══════════════════════╗ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:0B1220,45:0E7490,100:00F5D4&height=240&section=header&text=HAMZA%20SAFDAR&fontSize=58&fontColor=ffffff&fontAlignY=40&desc=I%20build%20AI%20that%20reads%2C%20retrieves%20%26%20decides&descSize=20&descAlignY=64&animation=fadeIn" width="100%" alt="Hamza Safdar"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=1000&color=00F5D4&center=true&vCenter=true&width=760&height=48&lines=RAG+%C2%B7+LLM+Tool+Calling+%C2%B7+AI+Agents;Turning+messy+PDFs+and+live+data+into+answers;CS+%40+FAST-NUCES+%7C+Dean%27s+List+x2;Co-Head%2C+Tech+Development+%40+GitHub+Campus+Club" alt="typing"/>
</a>

<br/><br/>

<a href="https://linkedin.com/in/hamzasafdar04"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00F5D4" alt="LinkedIn"/></a>
<a href="mailto:hamzasafdar7007@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FFB703" alt="Email"/></a>
<a href="https://github.com/Hamza-04-mav?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0D1117?style=for-the-badge&logo=github&logoColor=00F5D4" alt="Repos"/></a>
<img src="https://img.shields.io/badge/Dean's_List-Fall_'25_%26_Spring_'26-0D1117?style=for-the-badge&logo=googlescholar&logoColor=FFB703" alt="Deans List"/>
<img src="https://img.shields.io/badge/Karachi-Pakistan-0D1117?style=for-the-badge&logo=googlemaps&logoColor=00F5D4" alt="Karachi"/>

</div>

<br/>

```bash
$ whoami
hamza_safdar — CS undergrad @ FAST-NUCES Karachi  (2025 → 2029)

$ cat focus.txt
RAG · LLM tool calling · AI agents · live-data pipelines · full-stack web

$ git log --role
Co-Head, Tech Development @ GitHub Campus Club FAST-NUCES  (2026–27)

$ echo $MISSION
"Build reliable, data-driven software that solves real problems."
```

I care about the unglamorous parts of AI that make it actually work: **fallbacks, rate limits, secret handling, citations, and explainable scores.** A demo answers once. A system keeps answering.

<br/>

## ⚙️ How I Build

```mermaid
flowchart LR
    A["📥 INGEST<br/>PDFs · APIs · chats"] --> B["🧱 STRUCTURE<br/>Pandas · OCR · Vision"]
    B --> C["🔎 RETRIEVE<br/>FAISS + keyword"]
    C --> D["🧠 REASON<br/>LLMs + tool calling"]
    D --> E["🚀 SHIP<br/>FastAPI · Streamlit · React"]
    classDef n fill:#0D1117,stroke:#00F5D4,stroke-width:2px,color:#E6EDF3;
    class A,B,C,D,E n;
```

<br/>

## 🗂️ Case Files

### `01` · [ProspectIQ](https://github.com/Hamza-04-mav/ProspectIQ) — *plain-English criteria in, ranked leads out*

```text
natural-language criteria ─► live search API ─► Pandas ─► 0–100 score ─► CSV · Excel · Google Sheets
```

- **Explainable scoring:** every lead gets a Hot / Warm / Cool rating you can trace back to reasons
- **Website-presence detection** to separate ready-to-pitch leads from the rest
- **Reliability built in:** rule-based fallback parser + server-side credential handling, so API keys never reach the browser

`Python` `Pandas` `Streamlit` `Search API`

<br/>

### `02` · [Multimodal RAG Research Assistant](https://github.com/Hamza-04-mav/multimodal-rag) — *ask a paper anything, get the page number*

```text
PDF ─► text + tables + figures ─► OCR / vision ─► FAISS + keyword search ─► answer with page-level citations
```

- Reads what plain text extraction misses: **tables and figures**, not just paragraphs
- Hybrid retrieval (semantic + keyword) so exact terms and fuzzy meaning both land
- Tested on the *Attention Is All You Need* paper

`Python` `FAISS` `OCR` `Vision` `RAG`

<br/>

### `03` · WhatsApp AI Assistant — *the agent that knows when **not** to search*

```mermaid
flowchart TD
    U(["💬 User message"]) --> L{"🧠 Do I already know this?"}
    L -- "Yes" --> R1["✅ Answer directly"]
    L -- "Needs live info" --> T["🔧 Call web-search tool"] --> R2["✅ Answer with fresh context"]
    classDef n fill:#0D1117,stroke:#00F5D4,stroke-width:2px,color:#E6EDF3;
    classDef d fill:#0D1117,stroke:#FFB703,stroke-width:2px,color:#E6EDF3;
    class U,R1,T,R2 n;
    class L d;
```

- Native **LLM tool calling**: the model decides, not a hard-coded rule
- Session management + rate-limit handling so it stays up under real use

`Python` `Tool Calling` `Agents`

<br/>

### `04` · [CrewCompass](https://github.com/Hamza-04-mav/travel-planner-app) — *AI travel planner*

Born in the AI agents bootcamp as a Streamlit app and iterated toward a polished multi-page dashboard, with design benchmarked against products like Airbnb, Stripe, and Linear.

`Python` `Streamlit` `React` `TypeScript` `Vite`

<br/>

## 🔭 In the Lab

| 🧪 Building | 🌱 Leveling up |
|:--|:--|
| **UniBox** — a Chrome extension (Manifest V3) that uses AI to sort a university Gmail inbox into categories it discovers on its own | AI agents bootcamp: RAG, vector databases, prompt engineering, agent frameworks |
| **Finderr** — a student lost & found platform (Supabase auth, database, storage, realtime chat) | Production-grade backends, multimodal AI, agentic workflows |

<br/>

## 🧰 Skill Tree

| Domain | Arsenal |
|:--|:--|
| 🧠 **AI & Data** | ![LLMs](https://img.shields.io/badge/LLMs-0D1117?style=flat-square&logo=openai&logoColor=00F5D4) ![RAG](https://img.shields.io/badge/RAG-0D1117?style=flat-square&logoColor=00F5D4) ![Tool Calling](https://img.shields.io/badge/Tool_Calling-0D1117?style=flat-square&logoColor=00F5D4) ![FAISS](https://img.shields.io/badge/FAISS-0D1117?style=flat-square&logo=meta&logoColor=00F5D4) ![Pandas](https://img.shields.io/badge/Pandas-0D1117?style=flat-square&logo=pandas&logoColor=00F5D4) ![Groq](https://img.shields.io/badge/Groq-0D1117?style=flat-square&logoColor=00F5D4) ![Gemini](https://img.shields.io/badge/Gemini-0D1117?style=flat-square&logo=googlegemini&logoColor=00F5D4) |
| ⚙️ **Backend** | ![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00F5D4) ![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=00F5D4) ![REST](https://img.shields.io/badge/REST_APIs-0D1117?style=flat-square&logoColor=00F5D4) ![Streamlit](https://img.shields.io/badge/Streamlit-0D1117?style=flat-square&logo=streamlit&logoColor=00F5D4) ![Supabase](https://img.shields.io/badge/Supabase-0D1117?style=flat-square&logo=supabase&logoColor=00F5D4) |
| 🎨 **Frontend** | ![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=00F5D4) ![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=00F5D4) ![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=00F5D4) ![Vite](https://img.shields.io/badge/Vite-0D1117?style=flat-square&logo=vite&logoColor=00F5D4) ![Tailwind](https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=00F5D4) ![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=00F5D4) |
| 🔩 **Languages** | ![C++](https://img.shields.io/badge/C++-0D1117?style=flat-square&logo=cplusplus&logoColor=FFB703) ![Java](https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=FFB703) ![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=FFB703) ![JS](https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=FFB703) |
| 🛠️ **Tools** | ![Git](https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=00F5D4) ![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=00F5D4) ![VS Code](https://img.shields.io/badge/VS_Code-0D1117?style=flat-square&logo=visualstudiocode&logoColor=00F5D4) ![Vercel](https://img.shields.io/badge/Vercel-0D1117?style=flat-square&logo=vercel&logoColor=00F5D4) ![LaTeX](https://img.shields.io/badge/LaTeX-0D1117?style=flat-square&logo=latex&logoColor=00F5D4) |
| 📐 **Core CS** | `Data Structures & Algorithms` · `Object-Oriented Programming` · `Problem Solving` |

<br/>

## 🏅 Trophy Room

| | Milestone | When |
|:-:|:--|:--|
| 🎓 | **Dean's List of Honors** — FAST-NUCES | Fall 2025 · Spring 2026 |
| 🧑‍💻 | **Co-Head, Tech Development** — GitHub Campus Club FAST-NUCES | 2026–27 |
| 🏁 | **ACM Coders Cup** · **PROCOM'26 Code Sprint** · **PROCOM'26 Interstellar Intelligence** | 2025–26 |
| 🤝 | **Developers' Day '26 team** · CodeSprint challenges, ACM FAST-NUCES | 2026 |
| 👑 | **College Captain**, Bahria College NORE-1: led 30+ council members, events of 500+ people, 10+ industry sponsors | 2024–25 |
| 📜 | **Certified:** Amazon (Software Development · Java · DSA) · Google (Python) | — |

<br/>

## 📡 Telemetry

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=Hamza-04-mav&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00F5D4&text_color=C9D1D9&icon_color=FFB703&include_all_commits=true&count_private=true" alt="stats"/>
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hamza-04-mav&layout=compact&hide_border=true&bg_color=0D1117&title_color=00F5D4&text_color=C9D1D9" alt="languages"/>

<img src="https://streak-stats.demolab.com?user=Hamza-04-mav&hide_border=true&background=0D1117&ring=00F5D4&fire=FFB703&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00F5D4&sideLabels=8B949E&dates=8B949E" alt="streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Hamza-04-mav&bg_color=0D1117&color=00F5D4&line=00F5D4&point=FFB703&area=true&area_color=00F5D4&hide_border=true" alt="activity" width="100%"/>

</div>

<br/>

## ♟️ Your Move

I play chess, so I like thinking a few moves ahead. If you've got an **AI idea**, a **hackathon team to fill**, or a **project that needs a builder**, I'd like to hear it.

- 🎯 **Internships & collabs:** AI/ML engineering, agentic systems, full-stack
- 💼 **Freelance:** AI/ML and web development, plus content writing and academic editing


<div align="center">

<a href="https://linkedin.com/in/hamzasafdar04"><img src="https://img.shields.io/badge/Make_your_move-LinkedIn-00F5D4?style=for-the-badge&logo=linkedin&logoColor=0D1117" alt="LinkedIn"/></a>
<a href="mailto:hamzasafdar7007@gmail.com"><img src="https://img.shields.io/badge/Or_just_say_hi-Email-FFB703?style=for-the-badge&logo=gmail&logoColor=0D1117" alt="Email"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:00F5D4,55:0E7490,100:0B1220&height=110&section=footer&text=Let%27s%20build%20something%20that%20ships&fontSize=22&fontColor=ffffff&fontAlignY=62" width="100%" alt="footer"/>

</div>
