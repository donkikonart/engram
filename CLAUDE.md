# CLAUDE.md — Engram

Knowledge graph and persistent memory system for AI agents.

## Build and Test Commands
- **Test all**: `go test ./...`
- **Run Server**: `go run ./cmd/engram`
- **Setup**: `./setup.sh`

## Project Overview
Engram provides a structured way for agents to store and retrieve long-term context. It uses a graph-based storage model and supports multiple backends.

## Key Directories
- `cmd/`: Command-line tools (server and CLI).
- `internal/`: Core implementation.
- `skills/`: GSD/SDD skills that interface with Engram.
- `plugin/`: Agent-specific plugin definitions.

## Conventions
- **Go Version**: Go 1.24+
- **Testing**: Ensure all new features have unit tests in the corresponding `_test.go` file.
