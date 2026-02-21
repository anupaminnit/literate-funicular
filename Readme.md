# AImplify — Master Generative AI & Copilot in Your Daily Work

**Live site → [anupaminnit.github.io/literate-funicular](https://anupaminnit.github.io/literate-funicular/)**

A clean, interactive single-page resource that takes you from zero to confident with Generative AI and Microsoft Copilot 365 — covering the fundamentals, the architecture, and the practical techniques that actually make a difference in day-to-day work.

No fluff. No vendor hype. Just the technical understanding and ready-to-use prompts you need.

---

## What's Inside

The site follows a deliberate learning path across 11 sections:

| # | Section | What you'll learn |
|---|---------|------------------|
| 1 | **What is Gen AI** | How LLMs actually work, their capabilities, and their limits — plus 12 interactive flip cards defining key terminology |
| 2 | **How Gen AI Works** | Tokenisation, embeddings, self-attention, FFN layers, next-token sampling, and RLHF — the transformer pipeline explained |
| 3 | **What is RAG** | Why parametric knowledge fails for enterprise use and how Retrieval-Augmented Generation solves it |
| 4 | **How RAG Works** | The full two-phase pipeline: indexing (chunking, embedding, vector index) and query (retrieval, reranking, grounded generation) |
| 5 | **Copilot 365 as a RAG System** | How Copilot retrieves over Microsoft Graph, what data sources it covers, and how to prompt it effectively |
| 6 | **The RTCFC Framework** | A structured prompt anatomy: Role + Task + Context + Format + Constraints + Iterate |
| 7 | **Use Cases** | Production-ready prompts across 6 domains — Power Automate, Celonis, Email, Power Apps, Documentation, Code & RPA |
| 8 | **Prompt Engineering** | Advanced techniques: Chain-of-Thought, Few-Shot Exemplars, Self-Consistency, Schema Locking, Anti-Hallucination Grounding |
| 9 | **Using Copilot Effectively** | App-by-app guide across Outlook, Teams, Word, Excel, SharePoint, BizChat, and Copilot Studio |
| 10 | **Impact** | Quantified productivity data and qualitative improvements from real Copilot 365 deployments |
| 11 | **Prompt Cheatsheet** | 18 role-tagged, RTCFC-structured prompt templates covering every common scenario |

---

## Features

- **Interactive flip cards** — 12 key AI terminology cards that flip on click to reveal definitions
- **Tabbed prompt library** — 24+ production-ready prompt templates across 6 work domains
- **SVG architecture diagrams** — visual walkthroughs of the LLM inference pipeline and the RAG vs no-RAG comparison
- **Scroll reveal animations** — clean staggered entrance animations throughout
- **Fully responsive** — works on desktop, tablet, and mobile
- **Zero dependencies** — pure HTML, CSS, and vanilla JS. No build step, no frameworks, no npm

---

## Tech Stack

```
HTML5  ·  CSS3 (custom properties, grid, flexbox, 3D transforms)  ·  Vanilla JS
Fonts: Outfit · DM Sans · JetBrains Mono  (Google Fonts)
```

---

## Run Locally

```bash
git clone https://github.com/anupaminnit/literate-funicular.git
cd literate-funicular
# Open index.html in any browser — no server required
open index.html
```

Or just visit the **[live site](https://anupaminnit.github.io/literate-funicular/)** directly.

---

## Deploy Your Own

This is a single `index.html` file — deploy it anywhere static hosting is supported.

**GitHub Pages (recommended)**
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root directory
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

**Other options:** Netlify, Vercel, Cloudflare Pages — just drop the `index.html` file.

---

## Structure

```
literate-funicular/
├── index.html      # The entire site — self-contained
└── README.md
```

---

## Author

**Anupam Singh** — AI Developer  
[github.com/anupaminnit](https://github.com/anupaminnit)

---

*Built with the belief that understanding the technology — not just using it — is what separates good AI output from great AI output.*
