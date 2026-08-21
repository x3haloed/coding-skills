# Coding Skills

Coding Skills is a focused stack for building software whose claimed capabilities are real, whose architecture is understandable, and whose physical implementation avoids unnecessary machinery.

The stack separates three specialist disciplines and provides one orchestrator for work that must balance all three.

## Included skills

| Skill | Purpose | Entry point |
| --- | --- | --- |
| `causal-realization` | Make a capability exist as a complete, evidence-backed path from real input to observable output. | [`skills/causal-realization/SKILL.md`](skills/causal-realization/SKILL.md) |
| `topology-compression` | Reduce duplicated authorities, representations, boundaries, and coordination while preserving required behavior. | [`skills/topology-compression/SKILL.md`](skills/topology-compression/SKILL.md) |
| `embodiment-compression` | Preserve capability while reducing the machine resources and physical machinery required to embody it. | [`skills/embodiment-compression/SKILL.md`](skills/embodiment-compression/SKILL.md) |
| `truthful-system-construction` | Orchestrate causal realization, topology compression, and embodiment compression for substantial software construction and change. | [`skills/truthful-system-construction/SKILL.md`](skills/truthful-system-construction/SKILL.md) |

## Harness packaging

### Claude Code

Clone the repository and load the checkout as a plugin:

```bash
git clone https://github.com/x3haloed/coding-skills.git
claude --plugin-dir ./coding-skills
```

The Claude Code adapter is [`.claude-plugin/plugin.json`](.claude-plugin/plugin.json).

### OpenAI ChatGPT and Codex

The OpenAI adapter is [`.codex-plugin/plugin.json`](.codex-plugin/plugin.json). Add the checkout to a local or repository marketplace, install the plugin, restart the host, and verify skill discovery in a new task. Consult the current [OpenAI plugin packaging documentation](https://developers.openai.com/plugins/build/plugins) for marketplace setup.

These adapters establish repository structure only. Live harness discovery and representative journeys must be recorded before claiming discovery or behavioral verification.
