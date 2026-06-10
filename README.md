Developer tooling for agent systems — context enforcement, test harnesses,
protocol gateways, audit trails, and local workflows you can actually inspect.

Models are useful; the infrastructure around them is hard to test, constrain,
and recover. That's the gap I work in.

## Projects

### [Haechi](https://github.com/raeseoklee/haechi)

Self-hosted context enforcement for LLM APIs, MCP, vLLM, Ollama, and agent
traffic. Local proxy or stdio MCP wrapper; tokenize/redact payloads, audit
without raw secrets or PII. Developer preview.

### [A2A Sentinel](https://github.com/raeseoklee/a2a-sentinel)

Lightweight Go gateway for A2A traffic — rate limiting, auth modes, Agent Card
checks, audit logs, metrics, hot reload. Start here, grow into agentgateway.

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
