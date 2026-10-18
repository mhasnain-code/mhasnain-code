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

**`toolwall` v0.2** — a detector for indirect prompt injection at the tool-response boundary: regex rules plus a fine-tuned DeBERTa-v3 classifier. On InjecAgent cases with unseen tools *and* unseen attacker instructions it blocks all 95 attacks in both of InjecAgent's settings, with no false positives on 150 benign twins or 296 workplace emails. On BIPIA, run once after the model was frozen, it catches only 8 of 150 attacks. Both results are in the [5-page technical report](https://github.com/bryteai/toolwall/blob/main/paper/toolwall-v0.2-report.pdf).

#### Recent

- Found that the v0.1 judge (LoRA on Qwen2.5-7B) did not generalise: on external data it blocked 98 % of random Wikipedia pages. Replaced it and published why.
- Trained [`bryteai/toolwall-judge-v0.2`](https://huggingface.co/bryteai/toolwall-judge-v0.2) under a split-by-tool × split-by-instruction protocol; removed a container shortcut found during development.
- Published every test set, seed and per-row decision; each test file rebuilds byte for byte.
- Next: a task-aware judge that also sees the user's request, aimed at the BIPIA attacks v0.2 misses.

#### Reach

- web — [bryteai.studio](https://bryteai.studio)
- mail — `hasnain@bryteai.studio`
- security — [private vulnerability report on toolwall](https://github.com/bryteai/toolwall/security/advisories/new)

---

> I publish what I hit. Negative results stay published, and when a fix is made after seeing test results, I say so.
