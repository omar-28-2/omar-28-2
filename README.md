# `class OmarElhossiny : public BackendEngineer, AIEngineer, CompetitiveProgrammer`

```cpp
struct Omar {
    string role     = "Backend Software Engineer";
    string status   = "CS Graduate @ Nile University";
    double gpa      = 3.80;          // Highest Honors
    string rank     = "Codeforces Specialist";
    string mission  = "Seeking full-time Backend / SWE roles";
};
```

> "I treat architectural bottlenecks like competitive programming constraints —
> strictly optimizing for exact time and space complexity."

---

## 🌲 Tech Stack — represented as a Segment Tree (query any range, get the right tool)

```
                              ┌────────────────────┐
                              │      TechStack      │
                              │   (root, O(1) init) │
                              └──────────┬───────────┘
              ┌───────────────┬──────────┴───────────┬───────────────┐
              ▼               ▼                      ▼               ▼
        ┌───────────┐   ┌───────────┐          ┌───────────┐   ┌───────────┐
        │ Languages │   │ Backend/  │          │  AI/Data  │   │ Databases │
        │           │   │   APIs    │          │ Engineer  │   │           │
        └─────┬─────┘   └─────┬─────┘          └─────┬─────┘   └─────┬─────┘
              │               │                      │               │
   C#, Python,    ASP.NET Core, FastAPI,     RAG, Qdrant,      SQL Server,
   Java, C++      Django, .NET Core,         Cross-Encoder     PostgreSQL,
                   ASGI, REST APIs           Re-ranking, LLM    MySQL, Supabase
                                             Deployment
```

**Leaf-level tools & practices:** Git · Docker · Linux · CI/CD · Clean Architecture ·
EF Core · Design Patterns · Unit Testing

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
</p>

---

## 🔗 Career Path — a Union-Find (DSU) of merged experience sets

Every role gets `union()`-ed into the same connected component: **"Engineer who ships production systems."**

```python
parent = {}

def find(x):
    if parent[x] != x:
        parent[x] = find(parent[x])   # path compression
    return parent[x]

def union(a, b):
    ra, rb = find(a), find(b)
    if ra != rb:
        parent[ra] = rb               # union by rank(seniority)

# Timeline of unions (most recent first):
union("Head of Technical, NU Students' Union",              "Omar")   # Jun 2025 – Present
union("Vice Head, SWE Course @ GDG Nile University",         "Omar")   # Mar 2025 – Jun 2025
union("Full Stack .NET Trainee, DEPI",                       "Omar")   # Oct 2024 – May 2025
union("Junior Teaching Assistant, Nile University",          "Omar")   # Feb 2024 – Feb 2025
union("Backend Development Intern, Raya Trade",               "Omar")   # Aug 2024 – Sep 2024

assert find("Backend Development Intern, Raya Trade") == find("Head of Technical, NU Students' Union")
# -> True: one connected component, one engineer.
```

| Component (Role) | Interval | What got merged in |
|---|---|---|
| **Head of Technical** — NU Students' Union | Jun 2025 – Present | Led an engineering team to architect, deploy, and maintain campus-wide platforms & registration systems; owned full SDLC (design → review → deploy) |
| **Vice Head, SWE Course** — GDG Nile University | Mar 2025 – Jun 2025 | Co-designed curriculum with NU IECC; mentored 60+ junior students on end-to-end software architecture |
| **Full Stack .NET Trainee** — DEPI | Oct 2024 – May 2025 | Built full-stack apps with C#, ASP.NET Core MVC, SQL Server in Agile sprints; CI, unit testing, Docker |
| **Junior Teaching Assistant** — Nile University | Feb 2024 – Feb 2025 | Labs, grading, debugging mentorship for Python, Java, C++, Discrete Math |
| **Backend Development Intern** — Raya Trade | Aug 2024 – Sep 2024 | Built backend services (ASP.NET Core, C#) for the "Spend Smart" ecosystem; relational schemas, REST APIs |

---

## 🌳 Projects — a Binary(ish) Search Tree of things I've shipped
*(ordered by system complexity, not size)*

```
                         ┌─────────────────────────┐
                         │  NUverse (VR + RAG)      │  🏆 1st Place, ITCS Graduation Project
                         │  root: highest complexity│
                         └─────────┬────────────────┘
                    ┌──────────────┴───────────────┐
                    ▼                               ▼
        ┌────────────────────────┐        ┌─────────────────────────┐
        │ NUCPA Contest Platform │        │ ASR→QA Research Pipeline│
        │ nucpa.org              │        │ Egyptian Arabic Speech  │
        └────────────┬───────────┘        └────────────┬────────────┘
                      ▼                                 ▼
        ┌────────────────────────┐        ┌─────────────────────────┐
        │ University Coordination│        │ Full-Stack Photo Editor │
        │ System                 │        │                         │
        └────────────┬───────────┘        └─────────────────────────┘
                      ▼
        ┌────────────────────────┐
        │ RegexFlow: NFA/DFA     │
        │ Converter              │
        └────────────────────────┘
```

### 🥇 `NUverse` — AI-Powered Immersive Virtual University Ecosystem
**1st Place, ITCS Graduation Project**
Multi-modal platform bridging a Unity VR client and a Next.js web portal through an asynchronous FastAPI backend. Implements a **zero-hallucination, Two-Stage RAG pipeline** (Qdrant vector DB + cross-encoder re-ranking) for strict, fact-grounded retrieval — think of it as a lookup structure that refuses to return a wrong answer. Also powers a voice-to-voice VR Professor and an English/Arabic code-switching admissions chatbot.

### 🏗️ `NUCPA Contest Platform` — [nucpa.org](https://nucpa.org)
Full-stack competitive-programming contest system: team registration, algorithmic validation rules, admin monitoring dashboards. `Next.js` frontend, `Django` backend, `Supabase/PostgreSQL` storage layer — cleanly decoupled, like separating your I/O layer from your core algorithm.

### 🎙️ `ASR → QA Pipeline` — Analyzing Transcription Error Propagation (Research)
End-to-end Speech-to-Text → Question-Answering pipeline for Egyptian Arabic, built on the NileTTS dataset. Fine-tuned `Whisper-small` reaching **0.1168 WER / 0.0389 CER**, then benchmarked downstream QA with generative `AraT5` vs. extractive `AraELECTRA`. Finding: span-based supervision (AraELECTRA) is the more error-tolerant traversal strategy when the input signal (ASR transcript) is noisy.

### 🏛️ `University Coordination System`
ASP.NET Core MVC application managing the full admission funnel, degree programs, student applications, and secure transaction workflows — backed by a relational SQL Server schema.

### 🖼️ `Full-Stack Photo Editor`
Real-time matrix filters, live histogram generation, and FFT-based noise removal. `Next.js` + `Tailwind` frontend, `Python/Flask` image-processing backend — the pipeline itself is basically a chain of transform functions applied in sequence.

### 🔤 `RegexFlow` — Regex → NFA/DFA Converter
Parses regular expressions, converts to postfix notation, builds NFA tables, then minimizes to DFA state configurations — rendered as live transition graphs via Graphviz. Automata theory, visualized.

---

## 📊 Complexity Analysis of My Skillset

| Skill Area | "Time Complexity" (how fast I operate) | "Space Complexity" (breadth of coverage) |
|---|---|---|
| Backend Architecture (C#/.NET, FastAPI, Django) | O(log n) — experienced, efficient lookups | O(n) — broad framework coverage |
| RAG / AI Systems (Qdrant, re-ranking, LLM deploy) | O(n log n) — solid, still optimizing | O(n) — growing steadily |
| Competitive Programming (Codeforces Specialist) | O(1) amortized — pattern recognition kicks in fast | O(n) — many problem classes solved |
| Database Design (SQL Server, Postgres, MySQL, Supabase) | O(log n) — indexed thinking | O(n) — relational + managed platforms |

---

## 🗂️ `struct Education`

```cpp
struct Education {
    string institution = "Nile University";
    string degree       = "B.S. Computer Science";
    string timeline      = "2022 – Present (Expected Graduation: Summer 2026)";
    double gpa           = 3.80; // / 4.00, Highest Honors
};
```

## 📜 Certifications (leaf nodes, no children — terminal achievements)

- Full Stack .NET Web Developer — DEPI (May 2025)
- 2× ECPC Qualification (2024, 2025)
- Version Control — Meta (Sep 2024)
- Introduction to Databases — Meta (Aug 2024)

---

## 📬 `connect(Omar)` — O(1) lookup, always reachable

- 📧 omarelhossiny85@gmail.com
- 🌐 [LinkedIn](https://www.linkedin.com/in/omar-elhossiny)
- 💻 [Codeforces](https://codeforces.com/profile/HossHoss)
- 📁 [GitHub](https://github.com/omar-28-2)

## 🧠 Execution Philosophy

- 🧩 **Algorithmic Rigor:** Architectural bottlenecks get treated like competitive programming constraints — strict time/space complexity analysis, no hand-waving.
- 🚀 **Production-Ready:** Robust, decoupled systems with clean logic, built to scale under real-world, high-concurrency load.
- 🌳 **Structure Over Chaos:** Every system I build has a shape — a tree, a graph, a DAG — nothing is spaghetti by accident.

```cpp
// return type of this README
return "Backend Engineer, optimized.";
```
