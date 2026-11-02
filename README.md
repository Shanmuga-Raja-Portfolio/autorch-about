# autorch: resilient, local-first pipelines for local models

> Proprietary software by InferApps Tech PVT LTD. The source code is private. This page
> describes the project and what we're building.

One local workbench for a single GPU PC: an agent, unattended pipelines and model
management in one place. Every action is recorded with where it came from, so you can see
exactly what ran and why.

## What we're building

- **Pipelines that survive failure**: retries, timeouts, model fallback, crash-safe resume,
  and human review gates where they matter.
- **An agent with three risk modes** (ask, gated, auto) and a built-in adversarial reviewer.
- **Sandboxed shell commands** in containers, with secrets kept in the operating system's
  credential store.
- **Ready-made pipelines**: OCR, upscaling, image generation, depth maps, research and
  knowledge compiling.
- **A local dashboard and desktop app**, plus a scheduler, MCP tools and reusable skills.
- **Works with** Ollama, llama.cpp, Lemonade and InvokeAI.

## Status

In build.

---
Questions? Open an issue in this repository.
Part of [Shanmuga Raja Portfolio](https://shanmuga-raja-portfolio.github.io/).
