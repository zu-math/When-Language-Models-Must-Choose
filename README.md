# When Language Models Must Choose 

## Overview

This repository accompanies the study **“When Language Models Must Choose: Repeated Forced-Choice Responses in Publicly Deployed Conversational AI Systems.”** The study presents a repeated-session observational analysis of five publicly deployed conversational AI systems: **ChatGPT, Grok, DeepSeek, Claude, and Gemini**.

A fixed battery of five forced-choice questions concerning geopolitical, social, and cultural topics was administered through the systems' public consumer interfaces. The same wording, question sequence, and option arrangement were retained throughout the study. Twelve fresh sessions were conducted for each system during the recorded study period, yielding **60 session-level observations and 300 system-question responses**.

The study examines:

- Response concentration and variation across repeated sessions
- Differences in response distributions across system-question combinations
- Recurrence of particular alternatives under a fixed forced-choice protocol
- Departures from the requested single-option response format
- The value of repeated observation for distinguishing highly recurrent responses from more dispersed response patterns

The analysis concerns observable responses produced under the administered protocol. It does not interpret the selections as evidence of model preference, endorsement, categorical judgment, or persistent model-level behavior.

## Repository Structure

| Directory | Contents |
|-----------|----------|
| `Data/Processed/` | Consolidated response data used for the descriptive analysis and figures |
| `Data/Raw_Logs/` | Raw session records preserved from the public conversational interfaces, including the original responses and available session metadata |

## Key Methodological Features

- **Five conversational AI systems:** ChatGPT, Grok, DeepSeek, Claude, and Gemini
- **12 separate fresh sessions per system**, producing 60 session-level observations in total
- **Five questions administered together within each session** in the same fixed sequence and with the same option arrangement
- **300 system-question responses** across the complete study
- Public consumer interfaces were deliberately used so that the observations concern the deployed systems encountered by users rather than controlled API endpoints
- Fresh conversational contexts and session-isolation procedures were used to reduce carry-over between sessions
- A valid single-option response was defined as a response that unambiguously resolved to exactly one predefined A--D alternative
- Responses declining the requested choice, selecting multiple alternatives, or otherwise failing to resolve to one option were retained as **departures from the requested single-option format**
- Questions within a session are treated as related sequential observations rather than independent trials

## Data Availability

The repository provides raw session logs along with consolidated CSV record needed to inspect and reproduce the descriptive results. Raw logs preserve the recorded responses and available session metadata. Because public consumer interfaces were used, provider-side factors such as routing, system instructions, safety mechanisms, and interface changes were not experimentally controlled. The repository therefore represents a bounded observational record of deployed systems during the study period.

## Interpretation Note

The five questions were designed as exploratory probes, not as representative measures of geopolitical, social, or cultural attitudes. Some alternatives were not mutually exclusive; therefore, selections are interpreted as observable outputs under the fixed forced-choice protocol rather than as evidence of belief, preference, endorsement, or ideology. Results may differ under alternative wording, option order, isolated-question presentation, or different deployment periods.

## Citation

If you use materials from this repository, please cite the associated paper:

```bibtex
@inproceedings{Ali2027LLMChoice,
  title     = {When Language Models Must Choose: Repeated Forced-Choice Responses in Publicly Deployed Conversational AI Systems},
  author    = {S. Ali and N. M. Burqaiba},
  booktitle = {Proceedings of the 12th International Congress on Information and Communication Technology (ICICT 2027)},
  series    = {Lecture Notes in Networks and Systems},
  publisher = {Springer},
  year      = {2027},
  note      = {Accepted for publication},
  url       = {https://github.com/zu-math/When-Language-Models-Must-Choose}
}
```

