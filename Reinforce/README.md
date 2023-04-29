# REINFORCE

### Instructions

To see an interactive implementation of the REINFORCE algorithm (also known as Monte Carlo Policy Gradients) applied on OpenAI Gym's [Cartpole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py) environment, open notebook `Reinforce_Colab.ipynb` (by clicking on `Reinforce_Colab.ipynb` and then on 'Open in Colab' in the top left corner). This notebook runs on the Google `Colab` environment where access to GPUs is freely available. Alternatively, you can download the `Reinforce.ipynb` notebook and run locally (``PyTorch`` and OpenAI's ``gym`` libraries are required).

Experiment with changing the training parameters in the notebook to understand how the agent's learning is affected e.g. increase the number of training episodes, change the architecture of the neural network approximating the optimal policy, modify the learning rate for the Adam algorithm etc.

### Results 

In the [Cartpole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py) environment a pole (pendulum) is attached by an un-actuated joint to a cart which moves along a frictionless track. Starting from an upright position on the cart, our goal is to balance the pole (pendulum) by applying forces in the left and right direction on the cart.

Below is a gif showing a REINFORCE-trained agent balancing the pole.


![Reinforce trained agent](Reinforce_Cart_Pole_v0.gif)
