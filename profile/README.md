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
[![DaoBrew MCP](https://img.shields.io/badge/agent%20tools%20%E2%86%92-6d6a58?style=for-the-badge&labelColor=6d6a58)](https://github.com/DaoBrewAI/daobrew-wellness-mcp)

</div>

&nbsp;

## What we are building

**DaoBrew is a Causal Task Manager.**

Most task managers know deadlines, priorities, and projects. Wearables know your body. DaoBrew connects the two: it looks for the recurring work loop your body keeps reacting to, turns that loop into a task package, routes it to the work surface or agent you already use, and leaves the outcome honestly marked **verify pending** until the next comparable event.

> The task manager that knows which work your body keeps reacting to.

We are not building another calendar grid, recovery dashboard, content library, or all-purpose coding agent.

We are building the layer between body signals and unfinished work.

&nbsp;

## Product loop

```text
body signal + work context
        ↓
root-loop candidate
        ↓
task package
        ↓
your agent / calendar / issue tracker / work surface
        ↓
handled, not verified
        ↓
next comparable event
```

The important difference is the endpoint. A normal task manager stops at "done." DaoBrew keeps the proof honest: handled work is not claimed as solved until the next similar event gives the body a chance to respond.

&nbsp;

## Why this is different from task managers

| Existing category | What it is good at | What DaoBrew adds |
| --- | --- | --- |
| AI schedulers | Decide when work should happen. | Decide which recurring work loop is costing your body. |
| Issue trackers | Keep teams aligned around tasks, projects, and roadmaps. | Package the body-flagged loop into something a real work surface can close. |
| Wearables | Measure readiness, strain, HRV, sleep, and recovery. | Turn the signal into a closeable task instead of another dashboard. |
| AI agents | Execute bounded work when given context and permission. | Supply the task package, route policy, and verification state. |

DaoBrew does not replace Motion, Linear, GitHub, Claude Code, Codex, or Cursor. It decides what deserves to be routed there.

&nbsp;

## Public repos

The public side of DaoBrew is the reusable agent tooling we can share without exposing personal data, product internals, or proprietary signal models.

<table>
  <thead>
    <tr>
      <th align="left">Repository</th>
      <th align="left">What it is for</th>
      <th align="left">Start here when...</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/building-in-public"><b><code>building-in-public</code></b></a>
      </td>
      <td>Reusable skills, prompts, and operating systems we use while building DaoBrew.</td>
      <td>You want practical agent workflows, including <code>finding-your-unknowns</code> and <code>codex-loop-engineering</code>.</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/daobrew-wellness-mcp"><b><code>daobrew-wellness-mcp</code></b></a>
      </td>
      <td>Public MCP tooling for DaoBrew-style agent actions. The repo name is historical; the useful surface is now the agent bridge and Detonator-style task routing demo.</td>
      <td>You want to see how an agent can read a bounded state, schedule a block, route a task package, and mark the loop done / pending verification.</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/DaoBrewAI/.github"><b><code>.github</code></b></a>
      </td>
      <td>This organization profile.</td>
      <td>You want the current public map of DaoBrew.</td>
    </tr>
  </tbody>
</table>

&nbsp;

## What to try first

- **[`finding-your-unknowns`](https://github.com/DaoBrewAI/building-in-public/tree/main/finding-your-unknowns)** — a Claude Code skill that makes an agent surface task uncertainty before it starts building: goal frame, ranked hypotheses, discriminators, down-ranked blindspots, and deferred questions.
- **[`codex-loop-engineering`](https://github.com/DaoBrewAI/building-in-public/tree/main/codex-loop-engineering)** — a Codex loop system for long-running implementation work: local goal, tracker, constraints, handoff, verification, and continuation hygiene.
- **[`daobrew-wellness-mcp`](https://github.com/DaoBrewAI/daobrew-wellness-mcp)** — the public MCP bridge and demo surface. The repo name predates the current positioning; the useful direction is the agent-native route layer: read state, package work, act, and leave proof pending.

&nbsp;

## Open-source boundary

We open-source the parts that help builders work with agents better:

- skills and prompts that improve agent behavior,
- MCP / tool examples that show how agents can route bounded work,
- public demos of the task-package loop,
- operating docs that make long-running agent work more reliable.

We do not publish personal health data, personal baselines, proprietary signal models, or closed product internals.

&nbsp;

<div align="center">
  <sub><i>Find the loop. Route the task. Verify later.</i></sub>
</div>
