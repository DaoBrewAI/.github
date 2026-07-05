<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="DaoBrew AI — Causal Task Manager" src="./assets/banner-light.svg" width="100%">
</picture>

&nbsp;

[![daobrew.app](https://img.shields.io/badge/daobrew.app%20%E2%86%92-1a1815?style=for-the-badge&labelColor=1a1815)](https://daobrew.app)
&nbsp;
[![Building in Public](https://img.shields.io/badge/building--in--public%20%E2%86%92-c4543a?style=for-the-badge&labelColor=c4543a)](https://github.com/DaoBrewAI/building-in-public)
&nbsp;
[![Agent Tools](https://img.shields.io/badge/agent%20tools%20%E2%86%92-6d6a58?style=for-the-badge&labelColor=6d6a58)](https://github.com/DaoBrewAI/daobrew-wellness-mcp)

</div>

&nbsp;

## DaoBrew AI

We are building toward a **Causal Task Manager**: a task manager that uses body signals and work context to notice the recurring work loops your body keeps flagging.

The bet is simple: modern work tools know what is due, and wearables know how your body is doing. The missing layer is a system that connects the two, turns the loop into a closeable task package, and keeps the proof honest until the next comparable event.

DaoBrew is early. The product is still being shaped. The public repos here are the parts we can already share: agent skills, MCP experiments, and operating patterns we use while building.

&nbsp;

## What we publish here

<table>
  <thead>
    <tr>
      <th align="left">Repository</th>
      <th align="left">Why it exists</th>
      <th align="left">Useful if you...</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/building-in-public"><b><code>building-in-public</code></b></a>
      </td>
      <td>Reusable agent workflows, skills, and build notes from DaoBrew R&amp;D.</td>
      <td>Use coding agents and want sharper loops for discovery, planning, review, and continuation.</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/daobrew-wellness-mcp"><b><code>daobrew-wellness-mcp</code></b></a>
      </td>
      <td>MCP and agent-tooling experiments. The repo name is historical; the current direction is task-package routing and proof-state demos.</td>
      <td>Want to see how an agent can read bounded state, route a task, create an artifact, and leave verification pending.</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/.github"><b><code>.github</code></b></a>
      </td>
      <td>This organization page.</td>
      <td>Want the current public map of DaoBrew.</td>
    </tr>
  </tbody>
</table>

&nbsp;

## Start here

- **[`finding-your-unknowns`](https://github.com/DaoBrewAI/building-in-public/tree/main/finding-your-unknowns)** — a Claude Code skill for surfacing task uncertainty before an agent starts building.
- **[`codex-loop-engineering`](https://github.com/DaoBrewAI/building-in-public/tree/main/codex-loop-engineering)** — a Codex skill for long-running implementation loops: goal, tracker, constraints, handoff, verification, and continuation.
- **[`daobrew-wellness-mcp`](https://github.com/DaoBrewAI/daobrew-wellness-mcp)** — the current public MCP surface for agent actions and task-routing demos.

&nbsp;

## What we are not

DaoBrew is not a meditation app, a generic health dashboard, a calendar clone, or a replacement for your coding agent.

We care about the handoff: the moment a body signal becomes a concrete piece of work that can be routed, handled, and checked later.

&nbsp;

<div align="center">
  <sub><i>Body signals. Work loops. Task packages.</i></sub>
</div>
