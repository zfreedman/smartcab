# smartcab
Reinforcement learning applied to city driving simulation

# Description
The Jupyter notebook and HTML report in the smartcab files hold code for training a supervised learning agent for
a smartcab in a simulated city environment under US driving rules. The Q learning implementation for the learning
agent is in /smartcab/agent.py. This agent file is responsible for forming a driving policy in which the agent
takes it's environment (location, light color, other cars) in for processing in order to decide it's next action.
This agent is programmed to reach a destination while maximizing safety and minimizing lateness.
