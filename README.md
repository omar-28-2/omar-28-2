# Omar Elhossiny
**Backend Software Engineer** · CS Graduate, Nile University (Highest Honors, 3.80 GPA) · Codeforces Specialist
📧 omarelhossiny85@gmail.com · [LinkedIn](https://www.linkedin.com/in/omar-elhossiny) · [Codeforces](https://codeforces.com/profile/HossHoss) · [GitHub](https://github.com/omar-28-2)

> Actively seeking full-time Backend / Software Engineering roles.

---

## 🌲 Tech Stack — as a Tree

```mermaid
graph TD
    Root((Tech Stack))

    Root --> Lang(Languages)
    Root --> Back(Backend & APIs)
    Root --> AI(AI & Data Engineering)
    Root --> DB(Databases)
    Root --> Tools(Tools & Practice)

    Lang --> L1[C#]
    Lang --> L2[Python]
    Lang --> L3[Java]
    Lang --> L4[C++]

    Back --> B1[ASP.NET Core / MVC]
    Back --> B2[FastAPI — ASGI]
    Back --> B3[Django]
    Back --> B4[.NET Core Web API]
    Back --> B5[REST APIs]

    AI --> A1[RAG Pipelines]
    AI --> A2[Qdrant Vector DB]
    AI --> A3[Cross-Encoder Re-ranking]
    AI --> A4[LLM Deployment]

    DB --> D1[SQL Server]
    DB --> D2[PostgreSQL]
    DB --> D3[MySQL]
    DB --> D4[Supabase]

    Tools --> T1[Git / GitHub]
    Tools --> T2[Docker]
    Tools --> T3[CI/CD]
    Tools --> T4[Clean Architecture]
    Tools --> T5[EF Core]

    style Root fill:#2b2b2b,color:#fff,stroke:#888
    style Lang fill:#1f3a5f,color:#fff
    style Back fill:#1f3a5f,color:#fff
    style AI fill:#1f3a5f,color:#fff
    style DB fill:#1f3a5f,color:#fff
    style Tools fill:#1f3a5f,color:#fff
```

---

## 🔗 Career Path — Union-Find, visualized

Every role is a node. Over time, each one gets **union()'d** into the same connected component — one engineer, one growing tree of experience.

```mermaid
graph BT
    Omar((Omar<br/>root of the set))

    R1[Backend Dev Intern<br/>Raya Trade<br/>Aug–Sep 2024] --> R2
    R2[Junior TA<br/>Nile University<br/>Feb 2024–Feb 2025] --> R3
    R3[Full Stack .NET Trainee<br/>DEPI<br/>Oct 2024–May 2025] --> R4
    R4[Vice Head, SWE Course<br/>GDG Nile University<br/>Mar–Jun 2025] --> R5
    R5[Head of Technical<br/>NU Students' Union<br/>Jun 2025–Present] --> Omar

    style Omar fill:#7a2626,color:#fff,stroke:#fff,stroke-width:2px
    style R1 fill:#333,color:#fff
    style R2 fill:#333,color:#fff
    style R3 fill:#333,color:#fff
    style R4 fill:#333,color:#fff
    style R5 fill:#333,color:#fff
```

| Node | Interval | Path-compressed summary |
|---|---|---|
| **Head of Technical** — NU Students' Union | Jun 2025 – Present | Led an engineering team on campus-wide platforms & registration systems; owned full SDLC |
| **Vice Head, SWE Course** — GDG Nile University | Mar – Jun 2025 | Co-designed curriculum with NU IECC; mentored 60+ junior students |
| **Full Stack .NET Trainee** — DEPI | Oct 2024 – May 2025 | Built full-stack apps (C#, ASP.NET Core MVC, SQL Server) in Agile sprints |
| **Junior Teaching Assistant** — Nile University | Feb 2024 – Feb 2025 | Labs, grading, debugging mentorship: Python, Java, C++, Discrete Math |
| **Backend Dev Intern** — Raya Trade | Aug – Sep 2024 | Backend services (ASP.NET Core, C#) for "Spend Smart" ecosystem |

---

## 🌳 Projects — a Tree, ordered by system complexity

```mermaid
graph TD
    N0(("NUverse 🏆<br/>VR + Two-Stage RAG<br/>1st Place, ITCS Grad Project"))

    N0 --> N1["NUCPA Contest Platform<br/>nucpa.org"]
    N0 --> N2["ASR → QA Research<br/>Egyptian Arabic Speech"]

    N1 --> N3["University Coordination<br/>System"]
    N2 --> N4["Full-Stack<br/>Photo Editor"]

    N3 --> N5["RegexFlow<br/>NFA/DFA Converter"]

    style N0 fill:#7a5a1e,color:#fff,stroke:#fff,stroke-width:2px
    style N1 fill:#1f3a5f,color:#fff
    style N2 fill:#1f3a5f,color:#fff
    style N3 fill:#2b2b2b,color:#fff
    style N4 fill:#2b2b2b,color:#fff
    style N5 fill:#2b2b2b,color:#fff
```

**`NUverse`** — Multi-modal platform bridging a Unity VR client and Next.js web portal via an async FastAPI backend. Zero-hallucination, Two-Stage RAG (Qdrant + cross-encoder re-ranking) for fact-grounded retrieval; voice-to-voice VR Professor; English/Arabic code-switching admissions chatbot.

**`NUCPA Contest Platform`** — Full-stack contest system: registrations, algorithmic validation, admin monitoring. Next.js + Django + Supabase/PostgreSQL, cleanly decoupled.

**`ASR → QA Pipeline`** — End-to-end Speech-to-Text → QA for Egyptian Arabic (NileTTS dataset). Fine-tuned Whisper-small: **0.1168 WER / 0.0389 CER**. Benchmarked AraT5 (generative) vs. AraELECTRA (extractive) downstream.

**`University Coordination System`** — ASP.NET Core MVC app managing the admission funnel, degree programs, and secure transactions on a relational SQL Server schema.

**`Full-Stack Photo Editor`** — Real-time matrix filters, live histograms, FFT noise removal. Next.js + Tailwind frontend, Python/Flask image backend.

**`RegexFlow`** — Regex → postfix → NFA table → minimized DFA, rendered as live transition graphs via Graphviz.

---

## 🗃️ Skills — Hash Table Style

Each skill is hashed into a bucket by category. Collisions are chained.

```
 index │ bucket key        │ chain (collisions)
───────┼────────────────────┼──────────────────────────────────────────
  0    │ Languages          │ → C# → Python → Java → C++
  1    │ Backend/APIs       │ → ASP.NET Core → FastAPI → Django → .NET Core Web API → REST APIs
  2    │ AI & Data Eng.     │ → RAG → Qdrant → Cross-Encoder Re-ranking → LLM Deployment
  3    │ Frontend           │ → Next.js → HTML5 → CSS3 → JavaScript → Tailwind → Bootstrap → jQuery
  4    │ Databases          │ → SQL Server → PostgreSQL → MySQL → Supabase
  5    │ Tools & Practices  │ → Git → GitHub → Docker → Unit Testing → System Design → Design Patterns
  6    │ Competitive Prog.  │ → Codeforces Specialist → Advanced Algorithmic Thinking
```

```mermaid
graph LR
    H[("hash()")]

    H --> B0["bucket 0<br/>Languages"]
    H --> B1["bucket 1<br/>Backend/APIs"]
    H --> B2["bucket 2<br/>AI & Data Eng"]
    H --> B3["bucket 3<br/>Frontend"]
    H --> B4["bucket 4<br/>Databases"]
    H --> B5["bucket 5<br/>Tools"]
    H --> B6["bucket 6<br/>Comp. Prog."]

    B0 --> B0a[C#] --> B0b[Python] --> B0c[Java] --> B0d[C++]
    B1 --> B1a[ASP.NET Core] --> B1b[FastAPI] --> B1c[Django] --> B1d[.NET Core Web API]
    B2 --> B2a[RAG] --> B2b[Qdrant] --> B2c[Cross-Encoder] --> B2d[LLM Deploy]
    B3 --> B3a[Next.js] --> B3b[Tailwind] --> B3c[Bootstrap] --> B3d[jQuery]
    B4 --> B4a[SQL Server] --> B4b[PostgreSQL] --> B4c[MySQL] --> B4d[Supabase]
    B5 --> B5a[Git/GitHub] --> B5b[Docker] --> B5c[CI/CD] --> B5d[Design Patterns]
    B6 --> B6a[Codeforces Specialist] --> B6b[Algorithmic Thinking]

    style H fill:#7a2626,color:#fff,stroke:#fff,stroke-width:2px
```

---

## 🗂️ Education

```mermaid
graph TD
    Edu(("BS Computer Science<br/>Nile University"))
    Edu --> E1["GPA: 3.80 / 4.00<br/>Highest Honors"]
    Edu --> E2["2022 – Present<br/>Expected: Summer 2026"]

    style Edu fill:#1f3a5f,color:#fff
```

## 📜 Certifications — leaf nodes (no children)

```mermaid
graph TD
    Cert(("Certifications"))
    Cert --> C1[Full Stack .NET Web Developer — DEPI, May 2025]
    Cert --> C2[2× ECPC Qualification — 2024, 2025]
    Cert --> C3[Version Control — Meta, Sep 2024]
    Cert --> C4[Intro to Databases — Meta, Aug 2024]

    style Cert fill:#7a5a1e,color:#fff
```

---

## 📬 Connect — O(1) lookup

- 📧 omarelhossiny85@gmail.com
- 🌐 [LinkedIn](https://www.linkedin.com/in/omar-elhossiny)
- 💻 [Codeforces](https://codeforces.com/profile/HossHoss)
- 📁 [GitHub](https://github.com/omar-28-2)

## 🧠 Execution Philosophy

- 🧩 **Algorithmic Rigor** — architectural bottlenecks get treated like competitive programming constraints: strict time/space complexity analysis.
- 🚀 **Production-Ready** — robust, decoupled systems with clean logic, built to scale under real-world, high-concurrency load.
- 🌳 **Structure Over Chaos** — every system has a shape: a tree, a graph, a DAG — nothing is spaghetti by accident.
