# REINFORCE

### Instructions

Open the notebook `Reinforce_Colab.ipynb` (click on `Reinforce_Colab.ipynb` and then click on 'Open in Colab' in the top left corner) to see an application of the REINFORCE algorithm (also known as Monte Carlo Policy Gradients) to the OpenAI Gym's [Cartpole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py) environment. This notebook runs on the Google `Colab` environment where access to GPUs is freely available. Alternatively, you can download the `Reinforce.ipynb` notebook and run locally.

Experiment with changing the training parameters in the notebook to understand how the learning of the agent is affected e.g. increase the number of training episodes, size of the neural network approximating the optimal policy, the learning rate for the Adam algorithm etc.

### Results 

In the [Cartpole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py) environment a pole (pendulum) is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pole (pendulum) is placed upright on the cart and the goal is to balance it by applying forces in the left and right direction on the cart.

Below is a gif showing the REINFORCE-trained agent balancing the pole.


![Reinforce trained agent](Reinforce_Cart_Pole_v0.gif)
