# Contributing to Awesome OpenClaw Research

Thank you for your interest in contributing! This repository aims to be the most comprehensive collection of academic research on the OpenClaw ecosystem.

## What We Accept

- **Academic papers** about OpenClaw, Moltbook, ClawHub, or the broader agent ecosystem
- **Industry security reports** and technical analyses
- **Open-source tools** directly related to OpenClaw research
- **Datasets and benchmarks** from the ecosystem
- **Code repositories** associated with listed papers

## What We Don't Accept

- Skills or plugins (see [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills))
- Use case tutorials (see [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases))
- Promotional content or product announcements without technical substance
- Duplicate entries

## Paper Entry Format

```markdown
- **Paper Title** - Author1, Author2 et al. (Institution). Venue, Mon Year.
  [[Paper](arxiv-or-doi-link)] [[Code](github-link)]
  > One-line summary of the key contribution.
```

- Include the arXiv ID or DOI link
- Add code link only if publicly available
- Write a concise one-line summary focusing on the key contribution
- Place the paper in the most appropriate category per our [taxonomy](docs/survey/figures/taxonomy.md)

## How to Categorize

Our taxonomy follows a six-layer architecture-aligned structure:

| Layer | Category | Question It Answers |
|-------|----------|-------------------|
| L1 | Core Platform & Architecture | How is the OpenClaw framework extended? |
| L2 | Skill Ecosystem & Supply Chain | How secure/efficient is the skill marketplace? |
| L3 | Security & Trust | What are the threats, attacks, and defenses? |
| L4 | Agent Social Dynamics | How do AI agents behave socially on Moltbook? |
| L5 | Applications & Domains | Where is OpenClaw being applied? |
| L6 | Ecosystem Perspectives | What does the ecosystem look like holistically? |

If unsure about categorization, mention it in your PR and we will help.

## Submitting a PR

1. Fork the repository
2. Add your entry in the correct category section of `README.md`
3. Ensure alphabetical ordering within each subsection (by title)
4. Submit a PR with a clear title (e.g., "Add: SkillShield paper to Defensive Architectures")
5. Include a brief note on why this paper/resource belongs in the chosen category

## Quality Standards

- Papers must be publicly accessible (arXiv, DOI, or open-access venue)
- Industry reports must come from identifiable organizations
- Tools must have a public repository or documentation
- All links must be working at time of submission
