# HCOPE tutorial for SB3 agents
Tutorial on high confidence off-policy evaluation, using RL-Algorithms from SB3. 
## Overview
The tutorial(-jupyter-notebook) consists of 3 parts:

1. Short tutorial on importing/loading/training SB3 agents and working with policies. 
2. Overview on importance sampling and implementation of algorithms to estimate policy performance using off-policy evaluation only. 
3. Computing probabilistic lower bounds for estimates, computed in part 2.

### Running the tutorial locally
Clone repository to working direcetory

    git clone https://github.com/kashluga/sb3-hcope-tutorial.git

Create conda environment from `requirements.txt` 

    conda create --name hcope-tutorial --file sb3-hcope-tutorial/requirements.txt
Activate environment

    conda activate hcope-tutorial


Run jupyter-notebook 

`jupyter notebook sb3-hcope-tutorial/SB3-HCOPE-tutorial.ipynb`


### Dependencies
- [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3)
- [Pytorch](https://github.com/pytorch/pytorch)
- [OpenAi-Gym](https://github.com/openai/gym)
- [tqdm for progress bars](https://github.com/tqdm/tqdm)

#### Contributors
[Alejandro Arevalo Garzarro](https://www.instagram.com/garzaro002/?hl=en)
