### ShinRyu04

> *one endpoint, one key — the dragon eats free tiers.*

hey — i'm **Khalid** (`Indonesia`). i spend most of my time building **AI-first tooling**: native editors that agents can actually drive, local gateways that route every model behind one endpoint, and desktop apps that don't eat 2 GB of RAM just to render a text box.

sometimes the AI writes the commits. honestly, that's fine. somebody still has to supervise.

---

#### current focus — [Nakroth](https://github.com/ShinRyu04/Nakroth)

Native Rust GPUI IDE & multi-agent cockpit built for **Claude Code**, **Antigravity (`agy`)**, **Codex**, and **OpenCode** — 4 dedicated workspaces (`Editor`, `Fleet`, `Chat`, `Studio`), persistent `stream-json` workers, ConPTY terminal, and zero Electron overhead.

<a href="https://github.com/ShinRyu04/Nakroth">
  <img src="https://raw.githubusercontent.com/ShinRyu04/Nakroth/main/docs/screenshots/editor.png" alt="Nakroth IDE" width="100%" />
</a>

<sub>
  <a href="https://github.com/ShinRyu04/Nakroth/releases/latest">Download latest release</a> · Windows (<code>.exe</code> / <code>.zip</code>) · Linux (<code>.deb</code> / <code>.rpm</code> / <code>.AppImage</code>) · macOS (<code>.dmg</code> / <code>.pkg</code>)
</sub>

---

#### selected projects

| project | stack | what it does |
| :--- | :--- | :--- |
| [**Nakroth**](https://github.com/ShinRyu04/Nakroth) | `Rust · GPUI` | Native 120 FPS AI-first IDE & multi-agent cockpit with Fleet worktrees, Studio UI Designer, and persistent CLI workers |
| [**Zcode-Fucking-Mod**](https://github.com/ShinRyu04/Zcode-Fucking-Mod) | `Go` | OpenAI/Anthropic-compatible gateway for ZCode plan quota with a local operations dashboard |
| [**Autoclaw**](https://github.com/ShinRyu04/Autoclaw) | `JavaScript` | Self-hosted OpenAI/Anthropic gateway for AutoClaw & Z.ai — multi-account rotation, quotas, and watchdog |
| [**Zephyr**](https://github.com/ShinRyu04/Zephyr) | `TypeScript` | Lightweight code editor built around AI CLI workflows |
| [**Qoder-Local-Gateway**](https://github.com/ShinRyu04/Qoder-Local-Gateway) | `JavaScript` | Local gateway for Qoder CLI with OAuth login, multi-account profiles, and credit metering |
| [**kantor-agent**](https://github.com/ShinRyu04/kantor-agent) | `JavaScript` | Zero-config 3D office plugin that visualizes Claude Code & subagents working live |

---

#### stack

```text
languages   Rust · Go · TypeScript · Python
desktop     GPUI (Direct3D 11 / Vulkan / Metal) · Win32 COM · ConPTY · Tauri
infra       OpenAI/Anthropic local proxies · ACP / stream-json · SQLite FTS5 · Docker
```
