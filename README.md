# Reinforcement Learning

# Author
**Matthias Bartolo 0436103L**

## Preview:
<p align='center'>
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/f48e7ad0-9783-4c83-84a8-8e812795e276" style="display: block; margin: 0 auto; width: 90%; height: auto;">
</p>

## Description of Task:
In this completed project, the primary objective was to implement a **simplified Blackjack environment** and utilize it for training an agent using various **Reinforcement Learning** algorithms. The selection of Blackjack as the game of choice was driven by its simplicity, which lends itself well to the application and exploration of reinforcement learning techniques.

<p align='center'></br>
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/1c60e38f-f0ba-4997-9471-cb8c175384bf" alt="Blackjack Game" style="display: block; margin: 0 auto; width: 40%; height: auto;">
</p></br>

The project involved developing a representation of the Blackjack environment and implementing four different Reinforcement Learning algorithms to train the agent. The game of Blackjack utilized a standard deck of 52 cards and featured two key entities: the player and the dealer. At the beginning of each game, the player received two cards, while the dealer received one. The objective for both the player and the dealer was to achieve a total card value as close to 21 as possible without surpassing it. The player and the dealer had the option to either "stand" (stop taking cards) or "hit" (draw an additional card from the deck). The game concluded when both the player and the dealer chose to stand. The player with the highest total card value, not exceeding 21, was declared the winner. If either the player or the dealer exceeded 21 points, they lost the game, resulting in a win for the opposing player. The total value of a hand was determined by summing the individual card values.

To train the agent, the following four algorithms were successfully implemented: <br>

**1. Monte Carlo On-Policy Control** <br>
**2. SARSA On-Policy Control** <br>
**3. Q-Learning (SARSAMAX) Off-Policy Control** <br>
**4. Double Q-Learning Off-Policy Control** <br>

<p align='center'></br>
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/3703eea4-14d4-4216-9ac5-43f4fbc519bc" alt="RL Interaction Loop" style="display: block; margin: 0 auto; width: 70%; height: auto;">
</p></br>


Throughout the project, these algorithms were applied and evaluated in the Blackjack environment. The implementation involved training the agent to make optimal decisions based on the current state and available actions. The Reinforcement Learning algorithms learned to balance exploration and exploitation to maximize the expected rewards over time.

## Evaluation:
The evaluation of the aformentioned algorithms revealed some interesting insights. The different configurations had minimal impact on the number of unique states explored, indicating consistency across the algorithms. However, there were variations in the dealer advantage, with Monte Carlo exhibiting the highest advantage and SARSAMAX showing the lowest. This aligns with the overall win rates observed, where SARSAMAX performed better and Monte Carlo performed comparatively worse.

Additionally, it was noted that the convergence of the algorithms varied across different configurations. The last configuration exhibited the slowest convergence, attributed to the gradual decrease in exploration rate. In contrast, the other configurations demonstrated sudden convergence, likely due to a sharp transition to a high exploitation rate. This highlights the influence of exploration and exploitation rates on the convergence behavior of the algorithms.

Regarding Double Q-Learning, it is known to excel in noisy and uncertain environments, which was not the case in the Blackjack scenario analyzed. Consequently, the benefits of implementing Double Q-Learning in this specific problem were not prominent, and its performance was slightly inferior to standard Q-Learning. Both algorithms generally converge to the same optimum, and due to the simplicity of the problem, the advantages of Double Q-Learning were not clearly observed. However, there were instances where Double Q-Learning outperformed Q-Learning, indicating its potential in certain cases.

Nevertheless, in this particular study, it was observed that Double Q-Learning performed better than Q-Learning, achieving a lower dealer advantage of **0.008 (most optimal advantage)** compared to Q-Learning's 0.011.

<p align='center'>
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/c6a843ac-3b7c-4cb9-bf8f-b00bfb2233fb" style="display: block; margin: 0 auto; width: 43%; height: auto;">
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/57abe88c-9f46-4cbf-9e55-d5c892ab286c" style="display: block; margin: 0 auto; width: 40%; height: auto;">
</p>

Overall, the successful implementation and evaluation of the four Reinforcement Learning algorithms in the Blackjack environment have provided valuable insights into the agent's learning capabilities and its ability to make optimal decisions based on the given state and available actions. The project demonstrates the effectiveness and applicability of Reinforcement Learning techniques in training agents to play games and make informed decisions.

## Deliverables:
The repository includes a Blackjack environment with implementations of different RL algorithms and configurations<br />
 
