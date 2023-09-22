# CartPole Problem Solver with Q Learning

This Python project solves the CartPole problem from the OpenAI Gym environment using Q-learning. It leverages TensorFlow for reinforcement learning and can be configured to run on a GPU for faster performance, though it can also be run in CPU mode.

![dav_image](https://miro.medium.com/v2/resize:fit:1200/1*HNcp0AcTME4WRKqfoDc_dw.png)

## Table of Contents

- [**Introduction**](#intro)
- [**Dependencies**](#dep)
- [**Installation**](#install)
- [**Usage**](#usage)
- [**Results**](#results)
- [**Contribution**](#contr)

## Introduction <a name="intro"></a>

The CartPole problem is a classic reinforcement learning problem where the goal is to balance a pole on a moving cart. The agent must learn to apply forces to the cart to keep the pole balanced. This project uses Q-learning, a model-free reinforcement learning algorithm, to solve the problem.

## Dependencies <a name="dep"></a>

To run this code, you will need the following Python libraries:

- [**Gym:**] OpenAI Gym provides the environment for the CartPole problem.
- [**TensorFlow:**] TensorFlow is used for deep reinforcement learning.
- [**NumPy:**] NumPy is used for numerical operations.
- [**Math:**] Basic math operations are utilized in the code.
- [**Matplotlib:**] Matplotlib is used for plotting the rewards over episodes.
- [**Time:**] Time is used for tracking the execution time.

## Installation <a name="install"></a>

1. Clone the repository:
   `git clone https://github.com/mmhaashir/cartpole-q-learning.git`
   
3. Install the required dependencies:
   `pip install gym tensorflow numpy matplotlib`

## Usage <a name="usage"></a>

1. Run the CartPole solver script:
   `python cartpole_q_learning.py`
   
3. The script will simulate a specified number of episodes (default is 20,000) using Q-learning and print the sum of rewards obtained in each episode to the command line interface.
   
5. Once the simulation is complete, the script will generate a graph showing the rewards obtained over episodes.

## Results <a name="results"></a>

Upon running the CartPole solver, you can expect to see the sum of rewards for each episode printed to the CLI. Additionally, a graph displaying the rewards obtained over episodes will be generated and saved in the project directory.

## Contributing <a  name="contr"></a>

Contributions to this project are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
