# Brown Cyber Services

Research and open-source tooling on how AI agents behave on the open internet, and how to keep your own agents honest.

**Daniel F. Brown** · threat hunter, former Army cyber officer · [browncyber.com](https://browncyber.com)

## Projects

- **[agent-exposure-check](https://github.com/browncyber/agent-exposure-check)** · read-only checker for AI-agent exposure on hosts you own: hidden agent instructions, unauthenticated MCP servers, public A2A cards, open Ollama APIs. Python stdlib, Apache-2.0.
- **Stormseer** · passive tracker of AI-agent activity on the public internet (canaries, a honeypot, urlscan and Shodan cross-checks, surge detection). Write-up on the Amap agent incident coming to [browncyber.com/research](https://browncyber.com/research).
- **Measured Context** · measured boot for LLM agents: hash identity and policy before start, refuse on drift, judge outbound speech with a cold model. Upstream fix landed in [NousResearch/hermes-agent#144685](https://github.com/NousResearch/hermes-agent/issues/144685).

Everything here follows one rule: never contact a target you don't own. Canaries are disclosed where they're placed.
