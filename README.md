# Neox Sandbox

OS-level isolation for agent shell execution.

<p>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-22c55e?style=flat-square" alt="MIT" /></a>
  <a href="https://github.com/neoxlabs/neox"><img src="https://img.shields.io/badge/NeoX-Workstation-111827?style=flat-square" alt="NeoX" /></a>
</p>

| Platform | Backend |
|----------|---------|
| macOS | Seatbelt (SBPL), parameterized policies |
| Linux | bubblewrap / namespace isolation |

No dependency on NeoX product packages — isolation library only.

## Model

Capability axes (**read / write / network / process**) with tier presets and secret-path guardrails. Workspace-write tiers can keep `.git` and credential paths read-only when policy requires.

## Use with NeoX

NeoX Desktop and CLI use this sandbox for shell tool execution. The library is separately licensed so it can be audited and reused.

## License

[MIT](./LICENSE) © Neox Labs
