<h1>CS 370: Current and Emerging Trends in Computer Science</h1>
<h2>Adam Sissoko<br>
  Southern New Hampshire University</h2>
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
<p>My portfolio of projects is available for review in the <a href="https://github.com/adamsissoko/CS370" target="_blank">projects folder</a> on GitHub. Notable contributions include my work on the <a href="https://github.com/adamsissoko/CS370/tree/main/assignments/Cartpole" target="_blank">Cartpole Problem</a>, which demonstrates advanced algorithmic solutions, and the <a href="https://github.com/adamsissoko/CS370/tree/main/assignments/Pirate%20Treasure%20Hunt/" target="_blank">Pirate Treasure Hunt game</a>, an interactive program showcasing problem-solving and computational thinking.</p>

<p>For more information about the cartpole problem check out <a href="https://towardsdatascience.com/the-cartepole-problem-competitive-performance-with-particle-swarm-optimization-672f018ede3c" target="_blank"> this article</a> about it. This project involves developing a neural network that learns to balance a "pole" on a "cart" through reinforcement learning. My solution can be found in the link above, and below you can see a screenshot of my results.</p>
<div>
    <img src="https://github.com/adamsissoko/CS370/blob/main/images/solved.png" atl="[start]" style="width:200px;height:200px;">
</div>




<h4>Pirate Treasure Hunt</h4>
<p>This project was engaging and centered around creating a Deep Q-Learning algorithm using dual neural networks. The algorithm guides a "pirate" agent from the top-left corner to a "treasure" located at the bottom-right of a maze. Instead of using a manually populated Q-Table, the DQN estimates these values, helping the agent make optimized choices on its path through the maze.</p>

<p>
I was provided with a skeletal framework in a Jupyter Notebook that included only the DQN <a href="https://github.com/adamsissoko/CS370/blob/main/images/pirate_psuedocode.png" target="_blank">pseudocode</a>. My role was to flesh out this pseudocode into a functioning DQN that enables the agent to successfully navigate the maze. This required extensive research, both from textbooks and online sources. While the <a href="https://github.com/adamsissoko/CS370/blob/main/images/pirate_customcode.png" target="_blank">completed code</a> is my own creation, it incorporates elements from multiple references.
</p>

<p>
  The maze to solve is defined by the following matrix. A '0' indicates a space that the agent cannot move to.
</p>
<img src="https://github.com/adamsissoko/CS370/blob/main/images/matrix_maze.png" alt="[matrix]" style="width:400px;">

<p>This project was executed using Python and Keras. You can view the initial and concluding grid layouts below. For a comprehensive understanding of the task, refer to <a href="https://gotensor.com/2019/10/02/q-learning-an-introduction-through-a-simple-table-based-implementation-with-learning-rate-discount-factor-and-exploration/" target="_blank">this article</a>. My fully developed solution is accessible through the aforementioned link.</p>

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
  As you can see below, the agent solves the maze in 13 minutes...
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
The intriguing aspect of this specific project lies in the variability of the end solutions, attributed to the use of a Deep Q-Network (DQN) for maze-solving. The DQN fosters a level of exploration alongside exploitation, with a ratio set at 0.9 to 0.1. While the maze itself doesn't offer a plethora of solution paths, the agent still demonstrates some level of variability in its approach, thanks to the 'epsilon' variable that regulates the exploration factor in this endeavor.
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
To execute the above projects, as well as any others in this repository, you'll require Python and Jupyter Notebooks on your local machine. Additional libraries like matplotlib, Keras, TensorFlow, numpy, among others, are also needed. If you've installed Jupyter Notebooks but haven't set up these libraries, running a project will generate an error message indicating the missing library. Simply install the required packages using pip, and you'll be all set to proceed.
</p>



<h3>My Learning as a Computer Scientist</h3>
<p>In approaching problem-solving, whether in coding projects or in other aspects of life, I adopt a systematic and logical strategy. Being aware of the capabilities and limitations of the tools at my disposal allows for efficient progress. This way, it's far easier to maintain a balanced perspective; I can zoom out to appreciate the larger context and then zoom back in to address the intricate details, understanding how each contributes to the end goal.</p>
<p>
From an ethical standpoint, the computational power of computers surpasses any other systems available today, excelling in speed, precision, and problem-solving efficacy. Given this, it's imperative to adhere to ethical standards, particularly when working on projects that feature machine learning capabilities. Algorithms hold the potential for both beneficial and harmful impacts; thus, it's crucial for developers like myself to practice unbiased yet ethically grounded approaches during the development process.</p>
