# 🧠 Outskill Claude Expert

> A Claude Code skill for spec-driven development using Outskill workflows, teachings & resources, Snarktank PRD frameworks, and MCP workflows.
---

## 🎯 What Does This Do?

When you install this skill into Claude Code, it transforms Claude into a strategic project advisor. Before writing a single line of code, it will guide you to:

1. Use **Spec-Driven Development** — plan first, build second
2. Draft a full PRD using the **Snarktank Framework** (`it_process.md`)
3. Set up your project identity using **`CLAUDE.md`**
4. Map your app using the **"Chef (Claude) + Recipes (Skills) + Tools (MCPs)"** model
5. Prevent context rot using the **50% Context Rule**

---

## 🚀 Installation

Run this command inside any Claude Code project terminal:

```bash
npx skills add prakharmishra2026/outskill-claude-expert --skill outskill-claude-expert
```

Then trigger the skill inside Claude Code by typing:

> "Act as my Outskill Expert. I am starting a new project. Help me draft my `it_process.md` and `CLAUDE.md` files."

---

## 📂 Repository Structure

skills/
└── outskill-claude-expert/
└── SKILL.md ← The core AI skill (XML-tagged system prompt)

docs/
├── curated-links.md ← All Outskill frameworks, MCPs & essential tools
├── create-prd.md ← Snarktank: generate a PRD from a feature idea
├── generate-tasks.md ← Snarktank: break PRD into step-by-step tasks
├── process.md ← The full Snarktank workflow guide
├── claude logic flows.pdf ← Multi-tenant SaaS agent architecture diagrams
├── 50% context rules.pdf ← How to use memory.md and prevent context bloat
├── terminal foundations.pdf ← Terminal basics and environment variable safety
└── claudecode_transcripts/ ← Full Outskill masterclass session transcripts


> **Note:** `it_process.md`, `design.md`, `CLAUDE.md`, and `memory.md` are **not** static files in this repo — they are **generated fresh by the skill** each time you start a new project.

---

## ⚙️ Usage

1. Install the skill using the command above
2. Start a new Claude Code project
3. Trigger the skill with the prompt above
4. Let Claude guide you through drafting your PRD and project setup before touching any code

---

## 📚 Docs & Resources

Inside the `docs/` folder you will find everything you need to master Claude Code and agentic workflows:

- **`curated-links.md`** — Master hub of MCPs, frameworks, n8n, Compound Engineering, and more
- **`claude logic flows.pdf`** — Visual diagrams for multi-tenant SaaS agent architecture
- **`50% context rules.pdf`** — Deep dive into `memory.md`, `CLAUDE.md`, and the 50% rule
- **`terminal foundations.pdf`** — Terminal basics, navigation, and environment variable safety
- **Snarktank Toolkit** — `create-prd.md`, `generate-tasks.md`, `process.md`
- **`claudecode_transcripts/`** — Full raw session transcripts from Outskill masterclasses

---

## ⚖️ Legal Disclaimer & Fair Use Notice

**Educational Purpose:** This repository was created by a student, for students. It is an independent, community-driven resource to consolidate learnings, agentic workflows, and prompt engineering strategies for personal and educational use.

**Attribution:** The methodologies and foundational knowledge structured within this skill are heavily inspired by the curriculum provided by **Outskill (Growthschool)**. All credit for the original course material belongs entirely to Outskill and their respective instructors.

**No Affiliation:** This repository is not officially affiliated with, endorsed by, sponsored by, or supported by Outskill.

**Takedown Requests:** If you are an authorized representative of Outskill and believe any content here infringes on proprietary rights, please open an Issue or contact the repository owner directly. The requested content will be promptly and respectfully removed.

The `SKILL.md` implementation is provided under the **MIT License**, but this license does not extend to the underlying educational concepts or proprietary frameworks belonging to third parties.
