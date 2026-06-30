# R-MCTS: Retrospective Monte Carlo Tree Search

**Context-Aware Collaborative Embodied Task Planning with Sample-Efficient Self-Improvement via Retrospective Monte Carlo Tree Search**

Sanusi Mustapha Babansoro  
School of Computer Science and Engineering, UESTC, Chengdu, China

## Overview
R-MCTS enables LLM-based multi-agent embodied task planners to improve iteratively from recorded failures at zero additional live environment interaction cost.

## Contents
- `RMCTS.tex` — Full paper (LaTeX source)
- `RMCTS.pdf` — Full paper (PDF)
- `Figure1_RMCTS_System_Overview.png` — System overview diagram
- `Figure2_Retrospective_MCTS_Search.png` — Stage D retrospective search
- `Figure3_Cooperative_Markov_Game.png` — Two-agent architecture
- `Figure4_Self_Improvement_Cycle.png` — Self-improvement cycle
- `fig_dpo_loss.pdf` — DPO convergence curve (Experiment 5)

## Preliminary Validation Results
| Experiment | Result |
|---|---|
| Failure point detection | t* correctly identified |
| Scorer convergence | Loss → 0.000 |
| Retrospective search | Zero environment calls confirmed |
| LLM backbone (Mistral-7B) | 100% ALFRED action compliance |
| DPO fine-tuning | Loss 0.693 → 0.002 |

## Citation
Paper under review at Machine Intelligence Research (MIR), Springer.
