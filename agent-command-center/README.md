# Nexus — AI Agent Command Center

A single-file GUI for monitoring and controlling AI agents. Apple-inspired dark UI with glassmorphism, ambient lighting, and live simulation.

## Usage

```bash
# Just open in a browser — zero dependencies
open index.html
```

## Features

- **Agent cards** — live status badges, progress bars, task descriptions
- **Detail panel** — Overview, Logs, Tools, Pipeline tabs per agent
- **Metrics strip** — active agents, tasks/min, token usage, latency, success rate
- **Live simulation** — agent progress and metrics tick in real time
- **Command bar** — send instructions to any selected agent
- **Context menu** — right-click any agent to inspect, restart, pause, or terminate
- **Search** — filter agents by name, role, or task
- **Toasts** — non-intrusive notifications for all actions

## Customise

Replace the `AGENTS` array in `index.html` with your real agent data. The GUI is pure HTML/CSS/JS — no build step, no dependencies.
