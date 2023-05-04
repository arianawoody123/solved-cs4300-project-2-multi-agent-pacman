Download Link: https://assignmentchef.com/product/solved-cs4300-project-2-multi-agent-pacman
<br>
<h1></h1>

In this project, you will design agents for the classic version of Pacman, including ghosts. Along the way, you will implement both minimax and expectimax search and try your hand at evaluation function design.

As in Project 1, this project includes an autograder for you to grade your answers on your machine. This can be run with the command:

python autograder.py

The code for this project consists of several Python files, some of which you will need to read and understand in order to complete the assignment, and some of which you can ignore. Download search.zip from here http://ai.berkeley.edu/multiagent.html which will contain all the code and supporting files.

<h1>1      Files to edit</h1>

For all the problems in this project, you would have to edit just one python file namely:

<strong>multi-agents.py:</strong>, where all of your multi-agent search agents will reside.

<h1>2       Supporting Files</h1>

The following python files would help you in understanding the problem and the get you familiar with the different data structures and games states in Pacman.

<ul>

 <li><strong>py: </strong>The main file that runs Pacman games. This file describes a Pacman GameState type, which you use in this project.</li>

 <li><strong>py: </strong>The logic behind how the Pacman world works. This file describes several supporting types like AgentState, Agent, Direction, and Grid.</li>

 <li><strong>py: </strong>Useful data structures for implementing search algorithms.</li>

</ul>

<h1>3        Multi-Agent Pacman</h1>

For all the problem titles described below, please refer to the link http://ai.berkeley. edu/multiagent.html for the problem description and what is expected of each problem. As always autograder has different test cases against which you can run your program to check the correctness. Please ensure your code is readable and use comments in your code to make it more clear for the person reading your code.

For the questions asked below, please ensure your response is brief and to the point. Please dont write paragraphs of text as responses to these questions.

<h2>3.1      Reflex Agent</h2>

<ol>

 <li>(18 pts) Code implementation</li>

 <li>(1 pt) What feature (or features) did you use for your evaluation function?</li>

</ol>

<h2>3.2      Minimax</h2>

<ol>

 <li>(18 pts) Code implementation</li>

 <li>(1 pt) When Pacman believes that his death is unavoidable, he will try to end the game as soon as possible because of the constant penalty for living. Give an explanation as to why the Pacman rushes to the closest ghost in this case ?</li>

</ol>

<strong>3.3       Alpha-Beta Pruning </strong>

<ol>

 <li>(19 pts) Code implementation</li>

</ol>

<h2>3.4      Expectimax</h2>

<ol>

 <li>(18 pts) Code implementation</li>

 <li>(1 pt) You should find that your ExpectimaxAgent wins about half the time, while your AlphaBetaAgent always loses. Explain why the behavior here differs from the minimax case.</li>

</ol>

<h2>3.5       Evaluation Function</h2>

<ol>

 <li>(18 pts) Code implementation</li>

 <li>(1 pt) What features did you use for your new evaluation function?</li>

</ol>

<h1>4        Self Analysis</h1>

<ol>

 <li>What was the hardest part of the assignment for you?</li>

 <li>What was the easiest part of the assignment for you?</li>

 <li>What problem(s) helped further your understanding of the course material?</li>

 <li>Did you feel any problems were tedious and not helpful to your understanding ofthe material?</li>

 <li>What other feedback do you have about this homework?</li>

</ol>

<h1>5      Evaluation</h1>

Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes within the code, or you will wreak havoc on the autograder. If your code passes all the test cases in the autograder you would receive full points for the implementation.

However even if your code does not necessarily pass all the test cases, we would evaluate your code and then award you partial points accordingly. In such cases it would be even more beneficial if you could give a short description of what you tried and where you had failed and that would help us in giving you better points.