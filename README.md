# Speedrunning Social Development

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19702347.svg)](https://doi.org/10.5281/zenodo.19702347)
[![Release](https://img.shields.io/github/v/release/TimeLordRaps/speedrunning-social-development)](https://github.com/TimeLordRaps/speedrunning-social-development/releases/latest)
[![PDF](https://img.shields.io/badge/PDF-v0.2.0-red.svg)](https://github.com/TimeLordRaps/speedrunning-social-development/releases/download/v0.2.0/speedrunning-social-development-v0.2.0.pdf)

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

## Institutional & Computational Realization: Claim Garden
 
The meta-improvement principles formalized in this paper—particularly verified propositions, contestable leaderboards, adversarial glitch-hunting, and structured feedback flywheels—are operationally implemented in **[Claim Garden](https://claimgarden.com)** (and the underlying [Verifier Standard](https://github.com/TimeLordRaps/verifier) architecture).
 
In Claim Garden:
- **Refutable Claims as Unit of Value**: Computational claims and models submit bounded, refutable statements accompanied by reproducible verification receipts rather than relying on unverified proxies.
- **Adversarial Glitch-Hunting**: Automated verifiers and adversarial contributors receive standing for discovering counterexamples and refutations (Human-Adversarial and Tool-Adversarial exploration).
- **Leaderboard Feedback Flywheels**: Transparent public benchmarks and proposition tracking replace closed algorithmic manipulation with open verification flywheels.
 
## Current release state
 
- canonical paper source in `paper.tex` expanded to Version 0.2 (16 pages)
- canonical comparison figure included in the paper workflow
- release PDF frozen for `v0.2.0` and distributed via [GitHub Releases](https://github.com/TimeLordRaps/speedrunning-social-development/releases/tag/v0.2.0)
- Zenodo DOI minted: `10.5281/zenodo.19702347` (v0.1.0 initial; v0.2.0 release available)
 
## Suggested next steps
 
1. Make sure the `v0.2.0` GitHub release includes the frozen PDF (`speedrunning-social-development-v0.2.0.pdf`).
2. Add the DOI link to the GitHub release body if desired.
3. Post the paper publicly and invite hard critique.
4. Use later versions for refinements, pilots, and empirical follow-through.
