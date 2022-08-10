# AlphaZero
 [Implementation of the AlphaZero algorithm](https://medium.com/@_michelangelo_/monte-carlo-tree-search-mcts-alphazero-and-hopefully-muzero-for-dummies-11ad5d95d9d8 "Implementation of the AlphaZero algorithm")
 
## Introduction
This repo contains: 
- a simple but working implementation of the AlphaZero algorithm 
- an agent that uses the AlphaZero algorithm to play an openAI gym game (CartPole-v1)

### Project details

The code is an addition to the [MCTS](https://github.com/ciamic/MCTS "MCTS") algorithm implementation.

This is an implementation of an agent that uses an AlphaZero implementation in order to play the openAI gym game of CartPole.

### Getting Started

Execute the code in the notebook to train the agent! 

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name AlphaZero python=3.6
	source activate AlphaZero
	```
	- __Windows__: 
	```bash
	conda create --name AlphaZero python=3.6 
	activate AlphaZero
	```

3. Clone the repository, and then, install the required packages (see requirements).
```bash
git clone https://github.com/ciamic/AlphaZero.git
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `AlphaZero` environment.  
```bash
python -m ipykernel install --user --name AlphaZero --display-name "AlphaZero"
```

5. Before running code in a notebook, change the kernel to match the `AlphaZero` environment by using the drop-down contextual `Kernel` menu. 

### Requirements

- `Python 3`
- `numpy`
- `matplotlib`
- `gym`
- `Tensorflow`

