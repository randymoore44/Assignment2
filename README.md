Assignment 2: Blackjack Q-Learning

This assignment uses the Blackjack environment provided by Gymnasium. A tabular Q-learning agent is trained to learn when to hit or stick in order to maximize its expected reward.

The program investigates how different hyperparameter settings affect learning performance by testing different learning rates, discount factors, and initial exploration rates. It also evaluates a combined configuration using average reward, win rate, draw rate, and loss rate.

Setup Instructions

Install the required packages:

python -m pip install "gymnasium[other,toytext]" numpy matplotlib moviepy tabulate ipykernel

Run Instructions

Open the Jupyter notebook (.ipynb file).

Ensure the required packages are installed in the Python environment used by the notebook.

Run each cell in order, from top to bottom.

The notebook trains a baseline agent, tests different hyperparameter settings, evaluates the trained agents, and generates plots comparing their performance. It also attempts to record a video of the best-performing agent.

Generated Outputs

The notebook generates plots showing training performance for different hyperparameter settings and compares the baseline agent with the best-performing configuration. Any saved plots are written to PNG files, and video output is written into a mp4 file in the blackjack_video folder.
