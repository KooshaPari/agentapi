# AgentAPI

Unified API gateway for AI agent orchestration and tool integration.

## Overview

AgentAPI provides a standardized interface for building, orchestrating, and managing AI agents across multiple providers. It handles tool calling, context management, and stateful conversations.

## Features

- **Multi-Agent Orchestration**: Coordinate multiple agents in workflows
- **Tool Integration**: Standardized tool/function calling across providers
- **Stateful Conversations**: Persistent conversation state management
- **Provider Agnostic**: Works with OpenAI, Claude, Gemini, and more
- **Streaming Support**: Real-time streaming responses
- **Memory Systems**: Short-term and long-term memory for agents

## Quick Start

```bash
go install github.com/KooshaPari/agentapi@latest
agentapi serve --port 8080
```

## Documentation

- [Implementation Plan](docs/IMPLEMENTATION_PLAN.md)
- [Architecture Decision Records](docs/adr/)

## License

MIT
