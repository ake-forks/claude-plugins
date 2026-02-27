# Compete

Dispatch 2-4 sonnet subagents with diverse methodologies to review, research, or critique. Agents compete internally for quality; results are consolidated by importance.

## Installation

```
/plugin marketplace add juxt/claude-plugins
/plugin install compete
```

## Usage

Trigger with `/compete`, or ask Claude to "spin up agents", "dispatch agents", or "competing agents" for any parallel review or research task.

## How it works

1. **Classify** — review, research, or hybrid
2. **Select methodologies** — diverse lenses (adversarial, minimalist, archaeologist, etc.) or research sources (docs, forums, other projects)
3. **Dispatch** — 2-4 sonnet agents run in parallel with competition scoring rules
4. **Consolidate** — deduplicate, group by importance, present findings
