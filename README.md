# control-tower-docs

Design and planning documents for the Order-to-Delivery Control Tower, Problem Statement 3 of the LYB Mumbai Hackathon 2026 (Round 2).

All data in this project is fictional. "Plant X" is the fictional company from the hackathon brief.

## Documents

| Document | Purpose |
|---|---|
| [DESIGN.md](DESIGN.md) | Engineering design: requirements mapping, architecture, domain model, API and event contracts, ETA and risk calculation, security, verification and demo script |
| [PHASES.md](PHASES.md) | Execution plan for three owners: phases, exit criteria, critical path and cut list |
| [AI_USAGE.md](AI_USAGE.md) | Declaration of generative AI use, required by the hackathon rules |

These are the canonical copies. The code repositories link here:

- [control-tower-api](https://github.com/LYBHackathon/control-tower-api): Python, FastAPI
- [control-tower-web](https://github.com/LYBHackathon/control-tower-web): TypeScript, React

## Contract changes

Section 5 of `DESIGN.md` is the API contract. A pull request that changes the contract in `control-tower-api` links to the pull request here that updates `DESIGN.md`, and neither merges without the other.
