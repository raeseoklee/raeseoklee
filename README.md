Developer tooling for agent systems — context enforcement, test harnesses,
protocol gateways, audit trails, and local workflows you can actually inspect.

Models are useful; the infrastructure around them is hard to test, constrain,
and recover from when things fail. That's the gap I work in.

## Projects

### [Haechi](https://github.com/raeseoklee/haechi)

Self-hosted context enforcement for LLM APIs, MCP, vLLM, Ollama, and agent
traffic. Local proxy or stdio MCP wrapper; tokenize/redact payloads, audit
without raw secrets or PII.

### [A2A Sentinel](https://github.com/raeseoklee/a2a-sentinel)

Lightweight Go gateway for A2A traffic — rate limiting, auth modes, Agent Card
checks, audit logs, metrics, hot reload. Start here, grow into agentgateway.

### [Scanrail](https://github.com/raeseoklee/scanrail)

Developer-first security scan orchestrator. It wraps OSS tools behind one CLI so
checks can be installed, configured, run, normalized, and reported the same way
before PRs, releases, or handoffs.

### [Artifacty](https://github.com/raeseoklee/artifacty)

Local artifact exchange for LLM workflows over HTTP, CLI, and MCP. Agents can
publish, read, update, and continue from the same artifact without copying
context through chat.

### [Codexus](https://github.com/raeseoklee/codexus)

Local harness around OpenAI Codex CLI. Durable run ledgers, verification-gated
completion, bounded repair loops. "Done" means the check passed.

### [MCP Workbench](https://github.com/raeseoklee/mcp-workbench)

CLI for MCP server developers: inspect servers, generate YAML test specs, run
assertions, CI-friendly output.

- [VS Code extension](https://github.com/raeseoklee/mcp-workbench-vscode) — run specs and see failures in the editor
- [MCP server adapter](https://github.com/raeseoklee/mcp-workbench-mcp-server) — agents inspect, generate, and run tests as tools

## Connect

[GitHub](https://github.com/raeseoklee) · [LinkedIn](https://linkedin.com/in/raeseoklee)
