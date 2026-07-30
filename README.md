<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/mark-white.png">
    <img src="docs/assets/mark-dark.png" alt="NeoX" width="88">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/neox-white.png">
    <img src="docs/assets/neox-dark.png" alt="neox" width="180">
  </picture>
</p>

<h1 align="center">NeoX Sandbox</h1>

<p align="center">
  <strong>OS-level sandbox for agent tool execution.</strong><br>
  面向 Agent 工具执行的操作系统级沙箱。
</p>

<p align="center">
  <a href="https://github.com/neoxlabs/neox-sandbox/stargazers"><img src="https://img.shields.io/github/stars/neoxlabs/neox-sandbox?style=social" alt="GitHub stars"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License: MIT"></a>
</p>

<p align="center">
  <a href="https://neox-dev.com">Website</a> ·
  <a href="https://neox-dev.com/download">Download</a> ·
  <a href="https://neox-dev.com/docs">Docs</a> ·
  <a href="https://github.com/neoxlabs/neox">NeoX</a> ·
  <a href="mailto:support@neox-dev.com">Contact</a>
</p>

---

## Model

Capability axes (**read / write / network / process**) with tier presets and secret-path guardrails. Workspace-write tiers can keep `.git` and credential paths read-only when policy requires.

## Use with NeoX

NeoX Desktop and CLI use this sandbox for shell tool execution. The library is separately licensed so it can be audited and reused.

## License

[MIT](./LICENSE) © Neox Labs
