# AgentsUnderUncertainty-FrozenLake-v1
The primary goal of this project was to develop, test, and refine a strategy to enhance an agent's capability to navigate successfully within the FrozenLake-v1 environment.
# FrozenLake-v1 Reinforcement Learning Agent

## Overview
The primary goal of this project was to develop, test, and refine a strategy to enhance an agent's capability to navigate successfully within the **FrozenLake-v1** environment.  

To achieve this, the project focused on estimating the **state-action value function Q(s,a)** through the application of **Q-learning**, a reinforcement learning technique that enables an agent to learn from its interactions with the environment.  

By utilizing the derived **Q-table**, the agent is directed to make decisions that optimize its chances of reaching the designated goal while avoiding pitfalls.  

---

## Methodology
- **Environment:** FrozenLake-v1 (OpenAI Gym)
- **Approach:** Q-learning  
  - Initialize Q-table  
  - Update using the Bellman equation  
  - Balance exploration (ε-greedy) and exploitation  
- **Comparison:**  
  - **Q-learning Agent** vs **Random Agent**

---

## Results
- The Q-learning agent successfully improved its navigation performance compared to a random agent.  
- Effectiveness was assessed through metrics such as success rate and average rewards.  
- Balancing exploration and exploitation proved crucial to identifying an optimal path amid the uncertainties of the slippery surface.  

---

## How to Run
```bash
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Install dependencies
pip install -r requirements.txt

# Run the training script
python q_learning_frozenlake.py
