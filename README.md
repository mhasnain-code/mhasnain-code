<a href="https://bryteai.studio">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=00E5FF&center=false&vCenter=true&width=720&lines=Building+toolwall+%E2%80%94+a+tool-boundary+firewall+for+LLM+agents;Apache-2.0+%C2%B7+MCP-native+%C2%B7+framework-agnostic;NVIDIA+Inception+member" alt="Muhammad Hasnain — building toolwall" />
</a>

### Hi, I'm Hasnain.

```yaml
name:     Muhammad Hasnain
role:     Founder · AI-agent security
company:  bryteai.studio  (Bin Abdullah LLC, Brooklyn NY)
flagship: toolwall — Apache-2.0 tool-boundary firewall for LLM agents
focus:    indirect prompt injection · tool-call policy · MCP safety
license:  I ship Apache-2.0
member:   NVIDIA Inception
```

#### Now

Shipping **`toolwall` v0.1** — a 4-LoC defence that drops attack success rate from **100 % → 9.7 %** on a 200-case in-house bench (rules + LoRA judge), with **93.3 %** utility preserved. Apache-2.0, MCP-native, five framework adapters.

#### Recent

- **LoRA judge** on `Qwen/Qwen2.5-7B-Instruct` (Apache-2.0 substitute for the gated Llama base), trained on Modal A10G. Full rationale + dev-saturation disclosure in the model card.
- **`toolwall-bench-v0.1`** — 200 in-house cases across 7 attack families (base64, full-schema poisoning, markdown-exfil, multi-hop, rug-pull, tool-poisoning, unicode-tag), SHA256-pinned at release.
- **TypeScript port** `@bryteai/toolwall-core` — feature-parity with the Python core, ≤30 KB minified.
- **`create-toolwall-worker`** CLI scaffolds a Cloudflare Workers MCP server with OAuth 2.1 + KV audit log + Durable Object sessions, pre-wired with `policy.mcp()`.

#### Reach

- web — [bryteai.studio](https://bryteai.studio)
- mail — `hasnain@bryteai.studio`
- security — `security@bryteai.studio` (90-day coordinated disclosure)

---

> I publish what I hit. Honest negative results stay published. No number is adjusted after the fact.
