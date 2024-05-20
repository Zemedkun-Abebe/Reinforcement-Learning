# Reinforcement-Learning
<center><h1>Addis Ababa Institute of Technology</h1>
<h2>School of Information Technology and Engineering</h2>
<h2>Department of Artificial Intelligence</h2>

<h2>Reinforcement Learning</h2>

<h3>Exercise I: Introduction to Reinforcement Learning</h3>
<h4>Student Name: Zemedkun Abebe</h4></center>

![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/357ed43b-e4e4-4ace-b170-1903585192b7)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/9c3f66b0-5eab-498e-a3af-3832b3babad5)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/15883637-c70a-4f9e-b957-ce460c7fa68d)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/8a2328da-6ce0-42c9-a282-13e60d05af16)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/adc97899-36b4-47a7-8615-a5d814c84bdd)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/9a97331f-dcd8-42ed-b85b-32335d6da90b)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/6d63dd2d-67b6-45eb-a91f-2e2b8b8979c1)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/920390be-badc-47fb-aec2-e0dac7b86f55)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/fb24d4d2-9fdf-4c19-a4a8-78f5b3bd3eb9)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/f4b6821c-0c5f-4419-af2e-94ff1f2899e7)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/d05ccc3e-bf6f-4f56-8d70-e88b423fef21)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/4f72b70b-10b3-464c-9200-8364175cc89c)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/901af6c0-76f3-4245-8651-35c4d6a8878d)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/ba7e4e4e-3935-4fcd-b7aa-0d3e6fc9f1b5)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/5bcac863-2a13-45c7-b2e6-f0200f114899)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/44a4f171-0634-4642-923c-c37f4ac1e7ad)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/637e0aed-4c41-4ecf-9762-df8f39181059)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/88ebe462-e4fb-42c3-a959-67c9d98386a3)
![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/1c0ba780-3d51-4796-aa56-a40043fe0942)




















<h4>Topics</h4> 
<ul>
  <li>Value Iteration</li>
  <li>Policy Iteration</li>
  <li>Q-Learning</li>
  <li>Epsilon-Greedy Policy</li>
  <li>UCB Algorithm</li>
</ul>

<h4>Problem Definition</h4>
<p>Grid World Problem Definition</p>
<p><strong>Environment:</strong> The environment is a grid world represented by a 2D grid of size 𝑛×𝑚 (where n and m are the number of rows and columns in the grid). Each cell in the grid can be in one of three states: empty, obstacle, or goal.</p>
<p><strong>Agent:</strong> The agent starts at a designated starting point in the grid, which is an empty cell. The agent's goal is to navigate to the goal cell in the grid.</p>
<p><strong>Actions:</strong> The agent can take one of four actions at each step: move up, down, left, or right. The agent cannot move outside the grid or into cells containing obstacles.</p>
<p><strong>Rewards:</strong> The agent receives a reward of +10 for reaching the goal cell. The agent receives a reward of −1 for each step it takes (to encourage efficiency). If the agent enters a cell containing an obstacle, it receives a penalty of −10.</p>
<p><strong>Transition Dynamics:</strong> The agent's actions deterministically move the agent in the specified direction, as long as the move is within the grid and not blocked by an obstacle.</p>
<p><strong>Objective:</strong> The agent's objective is to find the shortest path from the starting point to the goal while minimizing the total cost (or maximizing the total reward).</p>
<p><strong>Starting Point and Goal:</strong> Specify the starting point and goal point in the grid. For example: Starting point: Cell (0, 0) Goal point: Cell (n-1, m-1)</p>
<p><strong>Define a set of obstacle cells in the grid:</strong> For example: Obstacles: A list of cell coordinates that contain obstacles.</p>
<p><strong>Initial Conditions:</strong> The agent starts at the starting point with no prior knowledge of the environment. The agent's initial policy and state values can be set to default values (e.g., zero).</p> 
</html>
