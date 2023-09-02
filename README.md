<h1>CS 370: Current and Emerging Trends in Computer Science</h1>
<h2>Adam Sissoko<br>
  Southern New Hampshire University</h2>


<h2>
Course Prerequisites
</h2>
CS 218 or CS 300
<h2>
Course Description
</h2>
<p>Students will explore advanced topics in Computer Science through analysis of authentic scenarios. Students will analyze the role of ethics in current trends within the field as well as apply fundamental concepts of the field to solve complex problems in new ways.
Course Competencies
</p>
<p>
This course covers the following competencies, which represent the knowledge and skills relevant to your field:
<ul>
    <li>CS-30424: Explain the basic concepts and techniques that pertain to artificial intelligence and intelligent systems
    <li>CS-30425: Analyze how algorithms are used in artificial intelligence to solve a variety of complex problems
    <li>CS-30426: Analyze current trends and emerging technologies in Computer Science for their impacts on society
</ul>
</p>
<hr>

<h3>My Projects</h3>
<h4>Cartpole</h4>
  <p>You can find all of my projects in the<a href="https://github.com/adamsissoko/CS370" target="_blank"> projects folder</a>.
  Some of my favorite projects are the <a href="https://github.com/adamsissoko/CS370/tree/main/Cartpole" target="_blank"> cartpole problem project</a> and the <a href="https://github.com/adamsissoko/CS370/tree/main/TreasureHuntGame/TreasureHuntGame" target="_blank"> pirate treasure hunt</a> project.
</p>
<p>For more information about the cartpole problem check out <a href="https://towardsdatascience.com/the-cartepole-problem-competitive-performance-with-particle-swarm-optimization-672f018ede3c" target="_blank"> this article</a> about it. This project involves developing a neural network that learns to balance a "pole" on a "cart" through reinforcement learning. My solution can be found in the link above, and below you can see a screenshot of my results.</p>
<div>
    <img src="https://github.com/adamsissoko/CS370/blob/main/images/solved.png" atl="[start]" style="width:200px;height:200px;">
</div>




<h4>Pirate Treasure Hunt</h4>
<p>The pirate treasure hunt game was a fun project to work on. This involved developing a Deep Q-Learning algorithm with a two neural networks to find a path to the "treasure". The "pirate" agent starts at the upper left corner of the maze, with the "treasure" in the lower right. The DQN approximates the values of the Q-Table (as opposed to a standard Q-Table populated manually). The pirate agent uses these values to make informed decisions about the best direction to take to solve the maze.
</p>

<p>
The majority of the code for this project was provided to me in a Jupyter Notebook file. The starter code for the DQN was nothing more than <a href="https://github.com/adamsissoko/CS370/blob/main/images/pirate_psuedocode.png" target="_blank">pseudocode</a>; my task was to complete it and get the network "learning" so the agent can finish the maze. This was done with a lot of outside research from both textbooks and internet sources. The <a href="https://github.com/adamsissoko/CS370/blob/main/images/pirate_customcode.png" target="_blank">final resulting code</a> is my own, but borrows from a variety of resources. I wrote up a <a href="https://github.com/adamsissoko/CS370/blob/main/writeups/DesignDefense.docx.pdf" target="_blank">Design Defense</a> document to summarize the project in more detail. This document features more information about how the DQN works in relation to traditional Reinforcement Learning without a DQN.
</p>

<p>
  The maze to solve is defined by the following matrix. A '0' indicates a space that the agent cannot move to.
</p>
<img src="https://github.com/adamsissoko/CS370/blob/main/images/matrix_maze.png" alt="[matrix]" style="width:400px;">

<p>
The project was run in python with Keras, and the starting and ending grids can be seen below. For more information about what this problem entails check out<a href="https://gotensor.com/2019/10/02/q-learning-an-introduction-through-a-simple-table-based-implementation-with-learning-rate-discount-factor-and-exploration/" target="_blank"> this article</a> about it. My solution can be found in the link above.</p>

<table>
    <tr>
        <th>Start</th>
        <th>Finish</th>
    </tr>
    <tr>
        <td><img src="https://github.com/adamsissoko/CS370/blob/main/images/start.png" atl="[start]" style="width:200px;height:200px;"></td>
        <td><img src="https://github.com/adamsissoko/CS370/blob/main/images/finish.png" atl="[finish]" style="width:200px;height:200px;"></td>
    </tr>
</table>
<p>
  As can be seen below, the agent solves the maze in approximately 13 minutes...
</p>
<table>
  <tr>
    <th>Run Time to Finding a Solution</th>
  </tr>
  <tr>
    <td><img src="https://github.com/adamsissoko/CS370/blob/main/images/run_detes.png" alt="[run deets]" style="width:400px;"></td>
  </tr>
 </table>

<p>
What is most interesting about this particular project is that, due to the DQN employed to solve the maze, the end solutions tend to vary to some degree in the path that the agent takes to get to the goal. The DQN allows some exploration, with an exploitation / exploration ratio of 0.9 to 0.1. The maze does not have a wide variety of solutions to find, but there is some variance when allowing the agent to solve through some exploring (the variable "epsilon" represents the exploration factor in this project).   
</p>
<table>
  <tr>
    <th>Solution 1</th>
    <th>Solution 2</th>
  </tr>
  <tr>
    <td><img src="https://github.com/adamsissoko/CS370/blob/main/images/alt_finish.png" atl="[start]" style="width:200px;height:200px;"></td>
    <td><img src="https://github.com/adamsissoko/CS370/blob/main/images/finish.png" atl="[finish]" style="width:200px;height:200px;"></td>
  </tr>
</table>

<p>
In order to run the projects above (and any others here in the repo) you will need Python installed on your machine, as well as Jupyter Notebooks. There are a variety of other libraries that you'll want to get as well (such as matplotlib, Keras, Tensorflow, numpy, and others), but once you have JN installed and attempt to run a project, you will be error-ed out with a message of which library you need. Just download and install the appropriate files using pip and you should be good to go!
</p>

<p>
  In addition to the above coding projects there were a variety of written assignments and "white paper" projects to submit. You can find them <a href="https://github.com/adamsissoko/CS370/tree/main/writeups" target="_blank"> in this folder </a>, along with some information about the requirements for each.
</p>

<h3>My Learning as a Computer Scientist</h3>
<p>
My approach to solving the above problems (and all others in any other aspect of my life) is methodical and logical. I typically know the limitations and abilites of the tools I am using to solve the problem, and using a one-step-at-a-time method helps me to work efficiently. I rarely have the problem in missing the "forest for the trees"; in fact, I'm very good at stepping back from the details and seeing the big picture for what it is, and then stepping back into the details with an understanding of how they effect the overall problem / solution.
</p>
<p>
Ethically speaking, computers have many abilities that cannot be found in any other system on Earth, including speed, accuracy, and solving problems efficiently. With this in mind, it is important to maintain an ethical mindset when developing software that, like the project above, has the ability to "learn" in a way that humans cannot. These algorithms can do many things for good, as well as for bad, and it is important for myself and others to remain unbiased but also ethical in our development approaches.
</p>
