# Projected-Gradient-Descent-Ascent (PGDA) Reinforcement Learning on FrozenLake

## Overview
This repository contains the implementation and experimentation of a tabular reinforcement learning agent—**(PGDA)**—applied to the slippery FrozenLake environment. The goal is to compare the performance of PGDA against the optimal policy obtained through value iteration.

The notebook demonstrates:
- Implementation of a PGDA agent with structured state-action buffers, adaptive exploration, and learning rate constraints.
- Conversion of the originally episodic environment to an infinite-horizon Markov Decision Process (MDP) by redirecting terminal state transitions.

## Repository Content
- `tt_primal_dual_rl_FrozenLake.ipynb`: Full experiment with environment setup, value iteration, PGDA agent, and result visualization.

## How to Run
```bash
# Clone the repo
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install gymnasium numpy matplotlib scipy tqdm

```
## Citation
This repository accompanies the following paper
