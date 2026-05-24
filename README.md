# Definition of Done (DoD) for AI-Augmented Teams

A sprint-goal-driven DoD template designed for development teams that integrate AI and static analysis into their quality assurance workflow.

## Overview

Traditional quality gates rely heavily on manual review. This DoD shifts baseline quality checks — readability, bug detection, security, performance — to static analysis and AI-assisted review, freeing the team to focus on what matters most: **achieving sprint goals and solving real customer problems**.

**Core philosophy:**
- Baseline quality → automated via static analysis & AI
- Human judgment → reserved for sprint goal achievement and business value

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

## AI Review Policy

Every phase requires an AI review pass. For each finding, the team must either:
- Address the issue, or
- Record an explicit justification for dismissal

This ensures AI feedback is never silently ignored — keeping the human-AI review loop accountable and auditable.

## Usage

1. Copy [`DoD.en.md`](./DoD.en.md) or [`DoD.ja.md`](./DoD.ja.md) into your repository or project wiki
2. Attach the checklist to each sprint / pull request as appropriate
3. Run AI review at each phase and log outcomes
4. Obtain PO sign-off before marking release readiness

## Contributing

Suggestions and improvements welcome — open an issue or submit a PR.

## License

[MIT](./LICENSE)
