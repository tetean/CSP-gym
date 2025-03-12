<h1>
<p align="center">
    <img src="properties/cover.png" alt="CSP-gym logo" width="600"/>
</p>
</h1>

<h4 align="center">

[//]: # ([![DOI]&#40;https://img.shields.io/badge/DOI-10.1038%2Fs41586--025--08628--5-blue&#41;]&#40;https://www.nature.com/articles/s41586-025-08628-5&#41;)

[//]: # ([![arXiv]&#40;https://img.shields.io/badge/arXiv-2312.03687-blue.svg?logo=arxiv&logoColor=white.svg&#41;]&#40;https://arxiv.org/abs/2312.03687&#41;)
[![Static Badge](https://img.shields.io/badge/Docs-cspgym.tetean.com-purple?style=for-the-badge)](cspgym.tetean.com)
[![Static Badge](https://img.shields.io/badge/Python-3.10%2B-yellow?style=for-the-badge)](https://python.org/downloads)

</h4>
# CSP Gym: A Reinforcement Learning Environment for Crystal Structure Prediction

CSP Gym is a benchmark environment for applying reinforcement learning to crystal structure prediction (CSP). The goal is to find the lowest energy configuration of a crystal by adjusting lattice parameters and atomic positions.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/tetean/CSP-gym.git
    cd CSP_gym
    ```

2. Install dependencies:
    
    ```bash
    pip install uv
    uv venv .venv --python 3.10 
    source .venv/bin/activate
    uv pip install -e .
    ```

3. Usage

    See the `examples/train.py` script for an example of training a PPO agent using Stable-Baselines3.

4. Citation

    If you use CSP Gym in your research, please cite:

    ```
    @article{wang2025cspgym,
      title={CSP Gym: A Benchmark Reinforcement Learning Environment for Crystal Structure Prediction},
      author={Wang, Xiean},
      journal={TBD},
      year={2025}
    }
    ```
