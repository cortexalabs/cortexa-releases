# Cortexa releases

Installers, auto-update manifests and server binaries for [Cortexa](https://cortexalabs.github.io/cortexa/), the encrypted collective cognition engine.

Grab the latest build from **[Releases](https://github.com/cortexalabs/cortexa-releases/releases/latest)**:

| Platform | Asset |
|---|---|
| Windows (x64) | `_x64-setup.exe` or `.msi` |
| Windows (ARM64) | `_arm64-setup.exe` |
| macOS (Apple Silicon) | `_aarch64.dmg` |
| macOS (Intel) | `_x64.dmg` |
| Linux server (Hive relay, MCP bridge) | `cortexa-hive-*`, `cortexa-mcp-*` |

Installed apps update themselves from this repo's `latest.json`. Every updater artifact is signed; the app verifies the signature before installing.

This repository only hosts release artifacts and is published automatically by the release pipeline.
