# Raoul Biagioni

I build LLM agents, MCP servers and the guardrails around them. I'm an AI Development Specialist at Ericsson, working on AI for telecom network software.

What I work on:

- **Memory and tooling for AI coding assistants** – making Claude Code, Pi and Kiro CLI learn from their mistakes across sessions.
- **Agent security** – prompt injection, and deterministic checks at the tool boundary that hold even when the model doesn't.
- **Autonomous agents for network operations** – multi-agent experiments on simulated telecom networks.

## Featured projects

| Project | What it is |
|---|---|
| [claude-recall](https://github.com/raoulbia-ai/claude-recall) | Persistent, local memory for AI coding assistants (Claude Code, Pi, Kiro CLI). It captures corrections and preferences automatically and injects them before the relevant tool call. TypeScript, MCP server, lifecycle hooks, SQLite. Published on [npm](https://www.npmjs.com/package/claude-recall). |
| [mcp-server-for-intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom) | MCP server that lets AI assistants search and analyse Intercom customer-support conversations and tickets. Listed on Glama. |
| [dgx-spark-prompt-injection-experiment](https://github.com/raoulbia-ai/dgx-spark-prompt-injection-experiment) | *A safe model is not a safe agent.* Three open models resisted prompt injection in plain chat, then leaked once wrapped in a minimal agent harness. A deterministic check at the tool boundary contained it. Reproducible on an NVIDIA DGX Spark. |
| [telco-constitution-lab](https://github.com/raoulbia-ai/telco-constitution-lab) | Local, OS-isolated lab for testing whether an agent working under a behavioural "telco constitution" shows engineer-like restraint when given a plausible but dangerous goal. |
| [nemoclaw-autonomous-network-agents](https://github.com/raoulbia-ai/nemoclaw-autonomous-network-agents) | Three autonomous agents (observer, analyst, planner) operating a simulated Irish 5G network inside an NVIDIA OpenShell/NemoClaw sandbox, with agent-driven scheduling and a fault-fatigue lifecycle. |
| [ai-discourse](https://github.com/raoulbia-ai/ai-discourse) | Multi-agent deliberation framework: agents submit typed interventions (interpret, challenge, introduce evidence) into shared proceedings, and understanding is versioned through synthesis and memory. |

## Tools I use

TypeScript / Node.js · Python · Model Context Protocol (MCP) · Claude Code · OpenAI-compatible LLM APIs · open-weight models · LangGraph · Docker / Kubernetes · SQLite · Playwright

## Contact

raoulbia.ai at gmail.com
