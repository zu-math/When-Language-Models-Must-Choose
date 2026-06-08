# How Five AI Models Quietly Rewrite the Way We See the World?

This repository contains the data, prompts, session logs, and supplementary materials for the study:

**"How Five AI Models Quietly Rewrite the Way We See the World?"**

## Overview

This study presents a controlled, multi-session analysis of behavioral tendencies in five major multimodal large language models (M-LLMs): **ChatGPT, Grok, DeepSeek, Claude, and Gemini**.

Using a set of five forced-choice questions spanning geopolitical, social, and cultural domains, the research examines how these models respond under tightly controlled conditions. The study focuses on:

- Distributional consistency and variations of responses across 12 independent sessions
- Model-specific patterns in positive vs. negative/critical framing
- The emergence of distinct behavioral signatures
- The use of a novel **Multi-Model LLM Evaluation Panel** to triangulate behavioral inclinations

## Repository Structure

| Directory          | Contents |
|--------------------|----------|
| `Data/Prompt`         | Full prompts used in the study, including meta-questions and output formatting instructions |
| `Data/Raw_Logs/`    | Raw responses from all sessions (including model self-reports from meta-questions) |
| `Data/Raw_Logs (LLM-EP)`       | Results from the Multi-Model LLM Evaluation Panel for Q-4 and Q-5 |
| `figures/`         | Response distribution plots for Q-4 and Q-5 |


## Key Methodological Features

- **12 independent sessions** per question–model pair
- **Strong isolation protocols**: Fresh accounts, incognito/private modes, separate browser profiles, and immediate history clearing
- **Meta-questions** included in every prompt to capture model identity and timestamps
- **Multi-Model LLM Evaluation Panel**: All five models served as independent binary judges to assess behavioral inclinations
- Focus on both **human-centered analysis** and **LLM-as-a-Judge** triangulation

## Data Availability

All session logs and LLM Evaluation Panel judgments are provided to support transparency and reproducibility.

## Citation

If you use materials from this repository, please cite the associated paper:

```bibtex
@article{sajid2026softpower,
  title   = {How Five AI Models Quietly Rewrite the Way We See the World?},
  authors  = {Sajid Ali, Noora Mohammad Burqaiba},
  year    = {2026},
  journal = {arXiv preprint},
  note    = {Data and materials available at \url{https://github.com/zu-math/LLM-Behavioral-Evaluation/}}
}

