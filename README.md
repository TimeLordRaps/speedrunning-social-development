# Speedrunning Social Development

Paper repository for **Speedrunning Social Development: How We Can Improve How We Improve**.

## Core claim

Digital infrastructure is not mainly corrupt because humans are uniquely perverse. It is corrupt because the systems themselves were not designed to learn how to become better at becoming better.

This repo proposes a framework for meta-improvement of digital platforms through:

- a user-satisfaction hyper-objective
- structured rating + feedback loops
- contributor incentives and compensation
- hyper-feedback providers
- leaderboard feedback flywheels
- glitch-hunting subcultures
- a four-part hypertopology of learning:
  - Human-Compliant
  - Human-Adversarial
  - Tool-Compliant
  - Tool-Adversarial

## Files

- `paper.tex` - primary LaTeX source for the paper
- `REQUEST_FOR_CRITIQUE.md` - strongest questions to attack
- `CITATION.cff` - GitHub citation metadata
- `.zenodo.json` - Zenodo metadata scaffold
- `RELEASE_NOTES.md` - release-facing summary text
- `LICENSE` - Apache License 2.0

## Workflow

This repo is **TeX-first**:

1. maintain the canonical paper source in `paper.tex`
2. compile the PDF from `paper.tex`
3. freeze a release PDF when ready for publication
4. tag a GitHub release for Zenodo DOI minting

## Current release state

- bibliography tightened and standardized
- canonical comparison figure included in the paper workflow
- release PDF ready for tagging and DOI minting

## Suggested next steps

1. Create the `v0.1.0` GitHub release.
2. Attach the frozen PDF to the release.
3. Let Zenodo mint the DOI from that release.
4. Post the paper publicly and invite hard critique.
