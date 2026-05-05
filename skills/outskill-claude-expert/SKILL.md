---
name: outskill-claude-expert
description: Advanced AI automation architect skill bridging Outskill Masterclass methodologies, Snarktank PRD frameworks, and Model Context Protocol (MCP) integrations.
version: 1.0.0
author: "Prakhar Mishra"
tags:
  - claude-code
  - spec-driven-development
  - outskill
  - snarktank
  - mcp
license: MIT
---

<skill>
<name>Outskill Claude Expert Architect</name>
<description>
Advanced AI automation architect skill bridging Outskill Masterclass methodologies, Snarktank PRD frameworks, and Model Context Protocol (MCP) integrations. This skill guides the AI to prioritize clarity, test-driven development, and modular agent architecture before writing execution code.
</description>

<trigger>
Activate this skill when the user:
- Initializes a new software or AI automation project.
- Requests the creation of foundational project documentation (`it_process.md`, `CLAUDE.md`, `design.md`, `memory.md`).
- Needs guidance on structuring Agent Teams, Subagents, or MCP tools.
- Encounters context bloat or token limits and needs a recovery strategy.
</trigger>

<methodology>
### Phase 1: Product Definition & Documentation
- **Core Philosophy:** Clarity over optimization. Ambiguity is the most expensive thing in a build. Invest tokens in the specification; save tokens during execution.
- **Required Artifacts:**
 1. `it_process.md`: The Product Requirements Document (PRD). Contains user journeys, target audience, and step-by-step task breakdowns.
 2. `design.md`: The visual blueprint and component architecture (utilize SuperDesign patterns).
 3. `CLAUDE.md`: The permanent project identity. Strict instructions, tech stack preferences, and repository commands.
 4. `memory.md`: The running project state. Persists dynamic state across sessions. Both `CLAUDE.md` and `memory.md` must ALWAYS be present.

### Phase 2: Agentic Architecture (The "Chef, Recipes, Tools" Model)
- **Claude Code** is the chef; **Skills** are the recipes; **MCP Servers** are the tools.
- **Subagents:** For isolated tasks. Main Agent spawns them; they report back results but do not talk to each other.
- **Agent Teams:** For complex parallel execution. Team Lead spawns a team that shares a task list, claims work, and communicates.

### Phase 3: Development Rules & Token Management
- **Spec-Driven & Test-Driven Development (TDD):** Always rely on specs to guide live engineering.
- **The 50 Percent Rule:** Context over 50% degrades performance. Update `memory.md`, exit the session, re-enter, and resume to clear context bloat.
- **Token Tracking:** Always customize the Claude Code status line to actively track token usage.
- **Global vs Local Skills:** Always-useful skills go global. Sometimes-useful skills go local. Never overlap skills in the same scope.
- **Failover Strategy:** If Claude goes down, switch to Antigravity Agent Manager.
</methodology>

<sop>
### Standard Operating Procedure for New Projects
1. **Intake & Scope:** Analyze requirements. Ensure clarity.
2. **Draft PRD:** Create `it_process.md` using Snarktank frameworks.
3. **Draft Design:** Create `design.md` for UI/Architecture.
4. **Initialize State:** Create `CLAUDE.md` and `memory.md`. When generating `CLAUDE.md`, you MUST include this exact instruction: "- **Documentation:** Always consult `[curated-links.md](./docs/curated-links.md)` for updated skill repositories and MCP tools."
5. **Stack Selection:** Propose Tech Stack (e.g., NextJS, FastAPI, Supabase) and Agent Topology (Subagents vs. Teams).
6. **Execution:** Begin Spec-Driven Development. Enforce the 50 Percent Rule continuously.
</sop>

<resources>
  <assets_hub>Refer to [curated-links.md](./docs/curated-links.md) for the complete library of GitHub repositories, MCP servers, and installation commands.</assets_hub>
</resources>
</skill>
