# Reinforcement Learning

# Author
**Matthias Bartolo 0436103L**

## Preview:
<p align='center'>
  <img src="https://github.com/mbar0075/Reinforcement-Learning/assets/103250564/f48e7ad0-9783-4c83-84a8-8e812795e276" style="display: block; margin: 0 auto; width: 90%; height: auto;">
</p>

## Description of Task:
In this completed project, the primary objective was to implement a **simplified Blackjack environment** and utilize it for training an agent using various **Reinforcement Learning** algorithms. The selection of Blackjack as the game of choice was driven by its simplicity, which lends itself well to the application and exploration of reinforcement learning techniques.

<p align='center'>
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Blackjack_board.JPG" style="display: block; margin: 0 auto; width: 40%; height: auto;">
</p>

The project involved developing a representation of the Blackjack environment and implementing four different Reinforcement Learning algorithms to train the agent. The game of Blackjack utilized a standard deck of 52 cards and featured two key entities: the player and the dealer. At the beginning of each game, the player received two cards, while the dealer received one. The objective for both the player and the dealer was to achieve a total card value as close to 21 as possible without surpassing it. The player and the dealer had the option to either "stand" (stop taking cards) or "hit" (draw an additional card from the deck). The game concluded when both the player and the dealer chose to stand. The player with the highest total card value, not exceeding 21, was declared the winner. If either the player or the dealer exceeded 21 points, they lost the game, resulting in a win for the opposing player. The total value of a hand was determined by summing the individual card values.

To train the agent, the following four algorithms were successfully implemented: <br>

**1. Monte Carlo On-Policy Control** <br>
**2. SARSA On-Policy Control** <br>
**3. Q-Learning (SARSAMAX) Off-Policy Control** <br>
**4. Double Q-Learning Off-Policy Control** <br>

<p align='center'><br>
  <img src="https://assets-global.website-files.com/621e749a546b7592125f38ed/6231efbede9e9af7f611ff68_fig%201.gif" style="display: block; margin: 0 auto; width: 70%; height: auto;">
</p>



Throughout the project, these algorithms were applied and evaluated in the Blackjack environment. The implementation involved training the agent to make optimal decisions based on the current state and available actions. The Reinforcement Learning algorithms learned to balance exploration and exploitation to maximize the expected rewards over time.

Overall, the successful implementation and evaluation of the four Reinforcement Learning algorithms in the Blackjack environment have provided valuable insights into the agent's learning capabilities and its ability to make optimal decisions based on the given state and available actions. The project demonstrates the effectiveness and applicability of Reinforcement Learning techniques in training agents to play games and make informed decisions.

## Deliverables:
The repository includes a Blackjack environment with implementations of different RL algorithms and configurations<br />
 
