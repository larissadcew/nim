# 🕹️ Nim - AI-Powered Strategy Game  

**Nim** is a classic mathematical strategy game where players take turns removing objects from heaps. This implementation integrates artificial intelligence to enable a computer player to make optimal moves using reinforcement learning techniques.  

---

## 🔍 What Does This Project Do?  

This project provides a simulation of the **Nim game** with a focus on AI development. The AI learns to play optimally through **Q-learning**, a model-free reinforcement learning algorithm, allowing it to improve its performance with experience.  

Key features include:  
- **Interactive Gameplay**: Play against an AI or simulate matches between AI agents. 🎮  
- **AI Training**: The AI improves its strategy over time using trial-and-error learning. 🧠  
- **Customizable Rules**: Modify heap sizes and configurations to experiment with gameplay. 🔧  

---

## 🛠️ Technologies Used  

This project uses Python and integrates key libraries for implementing reinforcement learning and managing gameplay logic:  

1. **Reinforcement Learning**:  
   - The AI uses **Q-learning**, a technique where it learns a Q-value (expected utility) for each possible state-action pair.  
   - Exploration vs. exploitation is handled via an epsilon-greedy approach, balancing between trying new moves and relying on known strategies.  

2. **NumPy**:  
   - Facilitates efficient array manipulation and computation during Q-table updates.  

3. **Custom Game Engine**:  
   - Handles game logic, including valid moves, state transitions, and winner determination.  

4. **Python OOP**:  
   - Object-oriented programming ensures modularity and clean separation between game logic and AI training.  

---

## 🔧 How It Works  

### 1. Gameplay  
- The game starts with multiple heaps of objects.  
- Players take turns removing objects from a single heap.  
- The player forced to take the last object loses.  

### 2. AI Training  
- **State Representation**: The current configuration of heaps is treated as the game state.  
- **Q-learning Process**:  
  - The AI begins with no prior knowledge and learns by playing multiple games.  
  - For each move, it updates the Q-value using the formula:  
    \[
    Q(s, a) \leftarrow (1 - \alpha) Q(s, a) + \alpha \left[ r + \gamma \max_a Q(s', a) \right]
    \]  
    Where:  
    - \( \alpha \): Learning rate.  
    - \( \gamma \): Discount factor for future rewards.  
    - \( r \): Immediate reward (e.g., +1 for winning, -1 for losing).  
    - \( s, a, s' \): Current state, action taken, and resulting state.  

### 3. Optimal Policy  
- Over time, the AI converges to an optimal policy, maximizing its chances of winning by selecting moves with the highest Q-values.  

---

## 📊 Performance  

- **Training Efficiency**: The AI achieves a competitive strategy after thousands of training games.  
- **Dynamic Adaptation**: The epsilon-greedy approach ensures exploration in early stages, gradually shifting toward exploitation of learned strategies.  

---

## 🎯 Applications  

This project showcases the power of reinforcement learning in decision-making tasks. Beyond gameplay, the principles used here are applicable to:  
- **Robotics**: Teaching machines to perform tasks through trial-and-error learning.  
- **Finance**: Developing algorithms for optimal investment strategies.  
- **Game Theory**: Studying strategic interactions in competitive environments.  

---

## 🌟 Why Use This Project?  

- **Educational Value**: Learn reinforcement learning concepts in an interactive and engaging way.  
- **Scalability**: Adaptable to more complex games and decision-making problems.  
- **Fun and Challenge**: Test your strategy skills against an ever-improving AI.  

---  

If you have questions or ideas for further improvements, feel free to reach out! 🚀  

