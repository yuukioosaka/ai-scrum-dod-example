```markdown
# Definition of Done (DoD)

A lightweight, sprint-goal-driven DoD template for modern software development teams.

## Overview

This DoD enforces quality at every phase of development — from high-level design through release — while leveraging static analysis and AI-assisted review to automate baseline quality checks.

**Core philosophy:**
- Baseline quality (readability, bug-free, security, performance) → automated via static analysis & AI
- Team focus → sprint goal achievement and customer problem resolution

## Files

| File | Language |
|---|---|
| [`DoD.en.md`](./DoD.en.md) | English |
| [`DoD.ja.md`](./DoD.ja.md) | Japanese |

## Checklist Phases

| Phase | Description |
|---|---|
| **High-Level Design (HLD)** | Architecture, interfaces, and deliverable completeness |
| **Program Code & Config** | Implementation, commits, PR readiness, scenario testing |
| **Integration Testing** | Coverage of sprint goals and all HLD requirements |
| **Low-Level Design (LLD)** | Detailed design artifact completeness |
| **Release Readiness** | PO acceptance, deployability |

## Usage

1. Copy [`DoD.en.md`](./DoD.en.md) or [`DoD.ja.md`](./DoD.ja.md) into your repository or project wiki
2. Attach the checklist to each sprint / pull request as appropriate
3. Complete AI review for each phase and log responses or dismissal rationale
4. Obtain PO sign-off before marking release readiness

## AI Review Policy

Each phase requires an AI review pass. For every finding, the team must either:
- Address the issue, or
- Record an explicit justification for dismissal

This ensures AI feedback is acted on deliberately, not ignored silently.

## Contributing

Suggestions and improvements welcome — open an issue or submit a PR.

## License

[MIT](./LICENSE)
```
