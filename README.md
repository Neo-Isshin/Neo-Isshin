<div align="center">

# Hi, I'm Neo

### Building local-first AI tooling that keeps your work, memory, and data under your control.

I build tools for people who work across multiple AI agents and want the results to remain useful after a session ends.

[![Homepage](https://img.shields.io/badge/Home-ailyre.com-bb8749?style=for-the-badge)](https://www.ailyre.com/)
[![Actanara](https://img.shields.io/badge/Flagship-Actanara-0B1F4D?style=for-the-badge)](https://github.com/Neo-Isshin/actanara)
[![TokenClock](https://img.shields.io/badge/Project-TokenClock-00A6D6?style=for-the-badge)](https://github.com/Neo-Isshin/TokenClock)
[![MuxLM](https://img.shields.io/badge/Project-MuxLM-516D9A?style=for-the-badge)](https://github.com/Neo-Isshin/MuxLM)

[![X](https://img.shields.io/badge/X-coming_soon-273b64?style=flat-square&logo=x)](https://x.com/)
[![WeChat](https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-coming_soon-07c160?style=flat-square&logo=wechat)](#)

</div>

---

## Actanara — shared memory for your AI work

<p align="center">
  <a href="https://github.com/Neo-Isshin/actanara">
    <img src="https://raw.githubusercontent.com/Neo-Isshin/actanara/main/docs/assets/banner.png" alt="Actanara" width="760">
  </a>
</p>

**Your agents do valuable work. Actanara makes sure that work does not disappear with the session.**

[Actanara](https://github.com/Neo-Isshin/actanara) *(formerly Open Nova)* is a structured, local-first AI asset operations system. It consolidates sessions, tasks, and evidence from Codex, Claude Code, Gemini CLI, OpenClaw, Hermes, OpenCode, Antigravity, and Cursor into one durable local layer, then turns them into:

- **shared memory across agents** — work done in Claude Code can be found and reused from Codex through a restricted read-only retrieval boundary (`nova-RAG` with a local lexical fallback);
- **a graph of work that actually happened** — `Nova-Task` derives tasks, status, and evidence from conversations, file changes, and tool results, not just manually written tickets;
- **automatic work narratives** — daily, weekly, and monthly reports that turn fragmented sessions into durable progress;
- **a local source of truth** — sessions, usage, generated assets, and task evidence stay in user-controlled storage with explicit integration boundaries.

Parser-first processing normalizes everything before any LLM sees it; your runtime data and generated assets remain under your control.

<p align="center">
  <a href="https://github.com/Neo-Isshin/actanara"><b>Repository</b></a>
  &nbsp;·&nbsp;
  <a href="https://neo-isshin.github.io/actanara/"><b>Website</b></a>
</p>

---

## TokenClock — AI usage at a glance

<table>
  <tr>
    <td width="38%" align="center">
      <a href="https://github.com/Neo-Isshin/TokenClock">
        <img src="https://raw.githubusercontent.com/Neo-Isshin/TokenClock/main/docs/screenshots/glass_en.png" alt="TokenClock Liquid Glass clock" width="360">
      </a>
    </td>
    <td width="62%" valign="middle">
      <b>One living dial for your AI coding tools.</b>
      <br><br>
      TokenClock reads local usage logs from Claude Code, Codex, Gemini CLI, OpenCode, and more, then turns them into an always-visible Liquid Glass view of tokens, messages, active tools, and per-session usage — broken down into sessions, models, and tools.
      <br><br>
      Local-only · zero upload · native Liquid Glass on macOS 26+.
      <br><br>
      <a href="https://github.com/Neo-Isshin/TokenClock"><b>Explore TokenClock →</b></a>
    </td>
  </tr>
</table>

---

## MuxLM — any provider, one short command

> Switch between providers and models in Codex, Claude Code, and OpenCode — without editing config files or scattering API keys.

```bash
cdx glm52    # Codex with GLM 5.2
cld k3       # Claude Code with Kimi K3
opc ds       # OpenCode with DeepSeek
```

One binary, three entry points (`cdx` / `cld` / `opc`). MuxLM is a lightweight **switcher, not a proxy**: the underlying CLI connects directly to your chosen provider, the launch config stays isolated from your global one, and nothing is left behind.

<p align="center">
  <a href="https://github.com/Neo-Isshin/MuxLM"><b>Explore MuxLM →</b></a>
</p>

---

## Ailyre — a personal corner of the internet

When I'm not building tools, I keep a small personal space at [**ailyre.com**](https://www.ailyre.com/) — a quiet homepage with an interactive lyre, an AI-news digest you can subscribe to, and room for curiosity to grow.

*保持好奇，自在生长。* (Stay curious, grow at ease.)

---

## What I care about

- **Local by default** — private work should not need a cloud account to become useful.
- **Interoperable by design** — knowledge should move across tools without one agent owning the whole workflow.
- **Durable outcomes** — sessions should become evidence, memory, and reusable assets instead of disposable chat history.
- **Explicit boundaries** — automation is most valuable when its permissions, data paths, and failure modes stay visible.

<div align="center">

*My Gods are in the Rain.*

</div>
