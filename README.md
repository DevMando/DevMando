# Hey, I'm Mando 👋

  Full-stack developer building tools that make development better. Currently focused on **local AI tooling**,
  **.NET/Blazor**, and **terminal-native UX**.

  ---

  ## What I'm Building

  ### 🤖 [MandoCode](https://github.com/DevMando/MandoCode)
  An open-source AI coding assistant that runs entirely in your terminal — no subscriptions, no vendor lock-in.
  Built with .NET 8, Blazor, and Semantic Kernel, powered by Ollama with support for both **local models** and
  **cloud-routed models** (like `kimi-k2.5:cloud`, `minimax-m2.5:cloud`, `qwen3-coder:cloud`).

  Run it fully offline with local weights, or tap into cloud models through Ollama's unified API — same interface
   either way.

  **Key features I've shipped:**
  - Agentic file operations (read, write, search, delete) via AI tool calling
  - Interactive diff approvals with inline diffs before any file is modified
  - Task planner that breaks complex requests into executable steps
  - Rich markdown rendering with syntax highlighting directly in the terminal
  - Background lofi/synthwave music player with animated equalizer
  - Clickable file paths, clipboard integration, and taskbar progress — all via terminal escape codes
  - Shell escape (`!cmd`) with `cd` interception and project root sync
  - Seamless switching between local and cloud models via `/config`

  **Currently working on:**
  - Thread safety hardening (concurrent function deduplication, chat history locking)
  - Path traversal security fix in the file system sandbox
  - Ctrl+C cancellation support for long-running AI requests
  - Retry resilience for streaming chat responses

  ---

  ## Tech I Work With

  **Day-to-day:** C#, .NET 8, Blazor, Semantic Kernel, Spectre.Console, ANSI/OSC escape codes

  **AI stack:** Ollama (local + cloud models), open-weight LLMs, function calling / tool use

  **Blockchain:** Solana ecosystem, Web3.js, on-chain program development

  **Game dev:** Actively exploring game development — building interactive systems is what got me into
  programming in the first place

  ---

  ## How I Build

  I treat my editor like a cockpit. On any given day you'll find me jumping between:

  - 🖥️ **Visual Studio** — heavy .NET work, debugging, profiling
  - 📝 **VS Code** — quick edits, web projects, extensions for everything
  - 🤖 **Claude Code** — AI pair programming from the terminal
  - 🧠 **Codex** — rapid prototyping and code generation
  - ⚡ **MandoCode** — because I built my own, so of course I use it - Ollama GO!🦙

  The best tool is the one that fits the problem. I use all of them.

  ---

  ## What Drives Me

  I believe the best developer tools are the ones that stay out of your way. MandoCode exists because I wanted an
   AI assistant that:
  - Works with any model — local weights on your GPU or cloud models through Ollama, your choice
  - Lives in the terminal — no browser tabs, no electron apps, no context switching
  - Feels native — rich diffs, clickable paths, taskbar progress, music — all through terminal escape codes

  If that sounds interesting, check out the repo, pull it down, and break things. PRs welcome.

  ---

  ## Connect

  [![GitHub](https://img.shields.io/badge/GitHub-DevMando-181717?style=flat&logo=github)](https://github.com/DevM
  ando)

  ---

  <sub>Currently vibing to lofi beats piped through terminal escape codes while an 80B cloud model thinks about
  your code.</sub>
