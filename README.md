# Reinforcement-Learning

![image](https://github.com/Zemedkun-Abebe/Reinforcement-Learning/assets/99493026/2d8907c2-7e45-4fcd-80d0-7d281a3239ac)
<center><h1>Addis Ababa Institute of Technology</h1>
<h2>School of Information Technology and Engineering</h2>
<h2>Department of Artificial Intelligence</h2>

<h2>Reinforcement Learning</h2>

<h3>Exercise I: Introduction to Reinforcement Learning</h3>
<h4>Student Name: Zemedkun Abebe</h4></center>

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
