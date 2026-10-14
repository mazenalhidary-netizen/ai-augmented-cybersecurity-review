# AI-Augmented Cybersecurity: A Comparative Analysis of Five Foundational Papers on Agentic AI and LLMs for Security Operations

**Author:** Mazen Abdulmalek Abdulrahman Saif Alhidary
**Affiliation:** Department of Cybersecurity, Sana'a University, Yemen
**Contact:** mazen.alhidary@su.edu.ye

## Overview

This repository contains the LaTeX source for a comparative review of five foundational papers on AI-augmented cybersecurity and Security Operations Centers (SOCs). The review evaluates scope, methodology, evaluation rigor, reproducibility, and risk coverage across the five works, and identifies six cross-cutting research gaps.

## Papers Analyzed

| # | Paper | Focus |
|---|-------|-------|
| 1 | Srinivas et al. (2025) | Survey of LLMs and agents across 8 SOC tasks |
| 2 | Kshetri (2025) | Agentic AI risk management and vendor case studies |
| 3 | Vinay (2025) | Five-generation architectural evolution of agents |
| 4 | Symbiotic HAI (2025) | Cognitive human–AI collaboration framework |
| 5 | Yelmo et al. (2025) | Empirical evaluation of LLM requirements generation |

## Six Cross-Cutting Gaps Identified

1. Empirical validation
2. Standardized benchmarking
3. Adversarial robustness
4. Human subject studies
5. Longitudinal tracking
6. Reproducibility

## Proposed Framework

**SOC-Agent-Bench** — a unified benchmarking framework combining datasets, tasks, agent generations, metrics, and human baselines from all five papers.

## Repository Contents

- `AI-Augmented Cybersecurity A Comparative Analysis of Five Foundational Papers on Agentic AI and LLMs for Security Operations.tex` — full IEEE-format LaTeX source
- `tables/` — extracted table sources (optional)
- `LICENSE` — MIT License
- papers/AI-Augmented SOC A Survey of LLMsandAgents for.pdf
- papers/Experimental_Evaluation_of_AI-Augmented_Cybersecurity_Requirements_Generation_Leveraging_LLMs_Capabilities.pdf
- papers/Symbiotic Human–AI Collaboration For Augmented Cybersecurity Operations.pdf
- papers/The Evolution of Agentic AI in Cybersecurity From Single LLM.pdf
- papers/Transforming cybersecurity with agentic AI to combat emerging.pdf

## How to Compile

Requires a LaTeX distribution with the `IEEEtran` class.

```bash
pdflatex AI-Augmented Cybersecurity A Comparative Analysis of Five Foundational Papers on Agentic AI and LLMs for Security Operations.tex
pdflatex AI-Augmented Cybersecurity A Comparative Analysis of Five Foundational Papers on Agentic AI and LLMs for Security Operations.tex   # run twice for references
