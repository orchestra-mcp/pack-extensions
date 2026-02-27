# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-02-27

### Added

- Plugin host architecture with QUIC + mTLS + Protobuf
- Orchestrator with plugin lifecycle management and message routing
- Go Plugin SDK (`sdk-go`) with fluent builder API
- Protobuf contract definitions (`proto` + `gen-go`)
- `storage.markdown` plugin — file-based storage with YAML frontmatter
- `tools.features` plugin — 34 feature-driven workflow tools
- `transport.stdio` plugin — MCP JSON-RPC to QUIC bridge
- `orchestra` CLI with `init`, `serve`, `install`, `plugins`, `update`, `uninstall` commands
- IDE auto-detection for 9 AI coding assistants (Claude, Cursor, VS Code, Windsurf, Codex, Gemini, Zed, Continue, Cline)
- Plugin generator script (`scripts/new-plugin.sh`)
- Sync and release scripts (`scripts/sync-repos.sh`, `scripts/release.sh`)
- Cross-platform release builds (darwin/linux, amd64/arm64)
- 62 unit tests + 1 end-to-end integration test
