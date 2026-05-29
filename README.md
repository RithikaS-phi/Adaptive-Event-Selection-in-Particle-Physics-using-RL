# Adaptive-Event-Selection-in-Particle-Physics-using-RL

**Rithika Shyam Kumar** · University of Bern · Reinforcement Learning Course

## About

This project models real-time particle collision event selection at CERN's Large
Hadron Collider as a Markov Decision Process, and trains two RL agents — a
tabular Q-learning agent and a Linear SARSA agent — to learn budget-aware
trigger policies.

See the attached report for full details.

## Contents

- `lhc_rl_trigger.ipynb` — environment, agents, training, and evaluation
- `results/` — training curves, policy heatmap, four-way comparison plots
- `report.pdf` — full project report

## Requirements

Python 3.9+, then:

```bash
pip install numpy gymnasium matplotlib
```
