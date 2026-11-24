# Raoul Biagioni

I build LLM agents, MCP servers and the guardrails around them. I'm an AI Development Specialist at Ericsson, working on AI for telecom network software.

What I work on:

- **Memory and tooling for AI coding assistants** – making Claude Code, Pi and Kiro CLI learn from their mistakes across sessions.
- **Agent security and evals** – prompt injection, and deterministic checks at the tool boundary that hold even when the model doesn't.
- **Autonomous and multi-agent systems** – experiments on simulated telecom networks and on structured agent deliberation.
- **Engineering practice for agents** – a framework and a review skill for taking agent projects from design to production.

## Featured projects

### Memory and tooling

| Project | What it is |
|---|---|
| [claude-recall](https://github.com/raoulbia-ai/claude-recall) | Persistent, local memory for AI coding assistants (Claude Code, Pi, Kiro CLI). It captures corrections and preferences automatically and injects them before the relevant tool call. TypeScript, MCP server, lifecycle hooks, SQLite. Published on [npm](https://www.npmjs.com/package/claude-recall). |
| [mcp-server-for-intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom) | MCP server that lets AI assistants search and analyse Intercom customer-support conversations and tickets. Listed on Glama. |

### Guardrails and evals

| Project | What it is |
|---|---|
| [dgx-spark-prompt-injection-experiment](https://github.com/raoulbia-ai/dgx-spark-prompt-injection-experiment) | *A safe model is not a safe agent.* Three open models resisted prompt injection in plain chat, then leaked once wrapped in a minimal agent harness. A deterministic check at the tool boundary contained it. Reproducible on an NVIDIA DGX Spark. |
| [telco-constitution-lab](https://github.com/raoulbia-ai/telco-constitution-lab) | Local, OS-isolated lab for testing whether an agent working under a behavioural "telco constitution" shows engineer-like restraint when given a plausible but dangerous goal. |
| [ai-chess-tutor](https://github.com/raoulbia-ai/ai-chess-tutor) | Locally run chess tutor. Stockfish and chess.js produce move commentary and hints without a model call; an LLM writes the end-of-game lessons and a second model fact-checks them before they are shown. Optional Maia human-like opponent (1100–1900) and an Elo-style rating. |

### Autonomous and multi-agent systems

| Project | What it is |
|---|---|
| [nemoclaw-autonomous-network-agents](https://github.com/raoulbia-ai/nemoclaw-autonomous-network-agents) | Three autonomous agents (observer, analyst, planner) operating a simulated Irish 5G network inside an NVIDIA OpenShell/NemoClaw sandbox, with agent-driven scheduling and a fault-fatigue lifecycle. |
| [ai-discourse](https://github.com/raoulbia-ai/ai-discourse) | Multi-agent deliberation framework: agents submit typed interventions (interpret, challenge, introduce evidence) into shared proceedings, and understanding is versioned through synthesis and memory. |

### Engineering practice

| Project | What it is |
|---|---|
| [agentic-ai-engineering-framework](https://github.com/raoulbia-ai/agentic-ai-engineering-framework) | Technology-agnostic framework for engineering agentic AI systems, from design to operation, plus an Agent Skill that reviews an agent repo against it or scopes a new agent. Works with Claude Code, Codex, Cursor and other SKILL.md tools. |

## Tools I use

TypeScript / Node.js · Python · Model Context Protocol (MCP) · Claude Code · OpenAI-compatible LLM APIs · open-weight models · LangGraph · Docker / Kubernetes · SQLite · Playwright

## Contact

raoulbia.ai at gmail.com
