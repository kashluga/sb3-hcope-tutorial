# HCOPE tutorial for SB3 agents
Tutorial on high confidence off-policy evaluation, using RL-Algorithms from SB3. 
## Overview
The tutorial(-jupyter-notebook) consists of 3 parts:

1. Short tutorial on importing/loading/training SB3 agents and working with policies. 
2. Overview on importance sampling and implementation of algorithms to estimate policy performance using off-policy evaluation only. 
3. Computing probabilistic lower bounds for estimates, computed in part 2.

### Running the tutorial locally
If you don't have any virtual environment set up follow the optional step below.
#### (Optional) Create conda environment
Install conda from this [link](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). In conda-prompt/terminal create environment:

    conda create --name hcope-tutorial
Activate environment

    conda activate hcope-tutorial
Install dependencies

    conda install pip
    pip install torch
    pip install gym
    pip install stable-baselines3
    pip install notebook
    pip install ipywidgets
    pip install tqdm
  
#### Running the jupyter-notebook
Clone repository to working direcetory

    git clone https://github.com/kashluga/sb3-hcope-tutorial.git

Open folder `cd sb3-hcope-tutorial`, run jupyter-notebook 

`jupyter notebook SB3-HCOPE-tutorial.ipynb`


### Dependencies
- [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3)
- [Pytorch](https://github.com/pytorch/pytorch)
- [OpenAi-Gym](https://github.com/openai/gym)
- [tqdm for progress bars](https://github.com/tqdm/tqdm)

#### Contributors
[Alejandro Arevalo Garzaro](https://www.instagram.com/garzaro002/?hl=en)
