<div align="center">

# DaoBrew AI

### **Stress, intervened — in three minutes.**

道 · brewed for the modern operator

[![npm](https://img.shields.io/npm/v/@daobrew/wellness-mcp.svg)](https://www.npmjs.com/package/@daobrew/wellness-mcp)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![TestFlight](https://img.shields.io/badge/iOS-TestFlight%20beta-black.svg)](#)

</div>

---

## 🌿 What this is

Most "wellness" stops at *interpretation* — here is your HRV, here is your stress score, good luck. **We close the loop.**

DaoBrew reads your wearable, classifies your current stress pattern, and runs a 3-minute music-guided breathing session that brings your nervous system back online.

**Detect → Intervene → Measure.** No mantras, no narrators, no tutorials.

> Wearables tell you *how you are*. We tell your body *how to come back*.

---

## 🫁 The Core — Music-Guided Resonance Breathing

> The active ingredient in stress relief is breathing at 4–7 breaths per minute, sustained for five minutes. Everything else exists to make that happen — without you having to think about it.

Music-guided resonance breathing is the entire product. The music's volume swells pace your inhale and exhale at your personal resonance frequency. With headphones, a theta binaural layer fades in. Apple Watch streams your heart rate and the session re-tunes itself mid-stream. By the time the music fades out, your HRV has measurably shifted.

**Why this approach, and not the alternatives:**

- Generic meditation apps are content libraries. We are an intervention engine. Calm and Headspace can't tell you what to do *right now, given your current state* — we can.
- Wearables (WHOOP, Oura, Apple Watch) are sensors. We are the action layer they were missing. We complement them; we don't compete.
- LLM-based "AI health coaches" got walked back across the industry in 2025–26 for liability reasons. Specialized, deterministic intervention is the platform-native answer.

The session is 3 minutes because that is the gap between async agent runs, between meetings, between the email you just got and the one you're about to send. Recovery infrastructure has to fit the 2026 high performer — not the other way around.

---

## 🔓 Open Source — Giving Back to the Community

We ship the engine three ways: a consumer iOS app, a B2B SDK for hardware partners, and **everything that benefits the developer community, in the open.**

### `@daobrew/wellness-mcp` — first wellness MCP server in production

The same engine that powers the App, exposed as an MCP server. Any agent — Claude Code, Cursor, Windsurf, Cline — can detect when its user is stressed and trigger a recovery session without leaving the editor.

```bash
npm install -g @daobrew/wellness-mcp
```

When Claude Code sees you've been debugging for 90 minutes and your HRV just dropped, the right answer is for the agent to call a wellness tool — not to suggest you "take a break." MCP governance moved to the Linux Foundation in late 2025; this is the architecture going forward. We were the first wellness company to ship there.

### Claude Skills we built and shipped

Building DaoBrew required AI tooling that didn't exist. Rather than keep it internal, we package them as installable [Claude Skills](https://docs.claude.com/en/docs/build-with-claude/agent-skills):

- **[`bazi-reader`](https://github.com/DaoBrewAI/building-in-public/blob/main/bazi-reader.skill)** — accurate Four Pillars chart generation, including monthly forecast. Handles edge cases (solar terms, zi-hour rollover) that LLMs alone get wrong.
- **[`design-language-translator`](https://github.com/DaoBrewAI/building-in-public/blob/main/design-language-translator.skill)** — converts founder-grade visual intent ("make it more 禅", "this feels off") into a precise designer brief, bilingual EN↔CN.
- **More planned** — pulse waveform feature extraction, TCM stress pattern classification reference implementations.

→ [`DaoBrewAI/building-in-public`](https://github.com/DaoBrewAI/building-in-public)

**Where we draw the line.** What helps the AI-native developer ecosystem stay healthy belongs in the commons. The prescription engine, the personal baseline calibration, and the proprietary pulse models trained on 200K+ annotated sessions stay closed. The line is intentional and clear.

---

<div align="center">

*If your nervous system runs hot, you are the user.*

</div>
