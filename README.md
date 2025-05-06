# cs7642-project-2-lunar-lander-solved
**TO GET THIS SOLUTION VISIT:** [CS7642 Project 2-Lunar Lander Solved](https://www.ankitcodinghub.com/product/cs7642-project-2-lunar-lander-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96298&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS7642 Project 2-Lunar Lander Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Lunar Lander

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 Problem 1.1 Description

For this project, you will be implementing and training an agent to successfully land the “Lunar Lander” (LunarLander-v2) in OpenAI gym. You are free to use and extend any type of RL agent.

1.2 Lunar Lander Environment

In this problem you will be working in an 8-dimensional state space, with six continuous state variables and two discrete ones. The action space is discrete. The four discrete actions available are: do nothing, fire the left orientation engine, fire the main engine, fire the right orientation engine. The landing pad is always at coordinates (0,0). Coordinates consist of the first two numbers in the state vector. The base reward for moving from the top of the screen to the landing pad depends on a number of factors. If the lander moves away from the landing pad it is penalized the amount of reward that would be gained by moving towards the pad. An episode finishes if the lander crashes or comes to rest, receiving an additional -100 or +100 points, respectively, on top of the base reward. Each leg-ground contact is worth +10 points. Firing the main engine incurs a -0.3 point penalty and firing the orientation engines incur a -0.03 point penalty, for each occurrence. Landing outside of the landing pad is possible. Fuel is infinite, so, an agent could learn to fly and land on its first attempt. The problem is considered solved when achieving a score of 200 points or higher on average over 100 consecutive runs. You are encouraged to look at the Lunar Lander source code for more information on the environment and reward structure.

1.3 State Representation

As noted earlier, there are four actions available to your agent: do nothing, fire the left orientation engine, fire the main engine, fire the right orientation engine. Additionally, at each time step, the state is provided to the agent as an 8-tuple:

(x,y,x ̇,y ̇,θ,θ ̇,legL,legR)

The state variables x and y are the horizontal and vertical position, x ̇ and y ̇ are the horizontal and vertical speed, and θ and θ ̇ are the angle and angular speed of the lander. Finally, legL and legR are binary values to indicate whether the left leg or right leg of the lunar lander is touching the ground.

1.4 Procedure

This problem is more sophisticated than anything you have seen so far in this class. Make sure you reserve enough time to consider what an appropriate solution might involve and, of course, enough time to build it.

• Create an agent capable of solving the Lunar Lander problem found in OpenAI gym

– Upload/maintain your code in your private repo at https://github.gatech.edu/gt-omscs-rldm

– Use any RL agent discussed in the class as your inspiration and basis for your program • Create graphs demonstrating

– The reward for each training episode while training your agent

– The reward per episode for 100 consecutive episodes using your trained agent – The effect of at least 3 hyper-parameters of your choosing on your agent

∗ You will select the ranges to be evaluated. 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– Lunar Lander 2 ∗ Evaluate your results in the context of the algorithm and the problem. Why do your results

make sense?

– Anything else you may think appropriate

<ul>
<li>We’ve created a private Georgia Tech GitHub repository for your code. Push your code to the personal repository found here: https://github.gatech.edu/gt-omscs-rldm</li>
<li>The quality of the code is not graded. You don’t have to spend countless hours adding comments, etc. But, it will be examined by the TAs.</li>
<li>You may use any function approximator to solve this problem, however we strongly recommend you use a non-linear function approximator such as a neural network. If you decide to train a neural network, you must train it using PyTorch as an automatic differentiation tool. Other neural network training libraries such as Tensorflow, Keras, Theano are not allowed. PyTorch is well liked amongst researchers for its pythonic feel, and we will hold a separate office hours to do a quick overview of PyTorch.</li>
<li>Make sure to include a README.md file for your repository
<ul>
<li>– &nbsp;Include thorough and detailed instructions on how to run your source code in the README.md</li>
<li>– &nbsp;If you work in a notebook, like Jupyter, include an export of your code in a .py file along with your notebook</li>
<li>– &nbsp;The README.md file should be placed in the project 2 folder in your repository.</li>
</ul>
</li>
<li>You will be penalized by 25 points if you:
– Do not have any code or do not submit your full code to the GitHub repository – Do not include the git hash for your last commit in your paper
</li>
<li>Write a paper describing your agent and the experiments you ran
<ul>
<li>– &nbsp;Include the hash for your last commit to the GitHub repository in the header on the first page of
your paper.
</li>
<li>– &nbsp;Make sure your graphs are legible and you cite sources properly. While it is not required, we recommend you use a conference paper format. For example https://www.ieee.org/conferences/ publishing/templates.html</li>
<li>– &nbsp;5 pages maximum – really, you will lose points for longer papers.</li>
<li>– &nbsp;Explain your experiments.</li>
<li>– &nbsp;Graph: Reward at each training episode while training your agent and discussion of results</li>
<li>– &nbsp;Graph: Reward per episode for 100 consecutive episodes using you trained agent and discussion of the results.</li>
<li>– &nbsp;Graph: Effect of hyperparameters and discussion of the results.</li>
<li>– &nbsp;Explanation of algorithms used: what worked best? what didn’t work? what could have worked
better?
</li>
<li>– &nbsp;Justify your choices
∗ Unlike project 1 there are multiple ways of solving this problem and you have a lot of discretion over the general approach you take as well as specific design decisions. Explain to the reader why, from amongst the multiple alternatives, you chose the ones you did.

∗ Same applies to hyperparameters experimentation
</li>
<li>– &nbsp;Explanation of pitfalls and problems you encountered.</li>
<li>– &nbsp;What would you try if you had more time?</li>
<li>– &nbsp;Save this paper in PDF format.</li>
<li>– &nbsp;Submit to Canvas!</li>
</ul>
</li>
<li>Using a Deep RL library instead of providing your own work will earn you a 0 grade on the project and you will be reported for violating the Honor Code.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
– Lunar Lander 3 1.5 Notes

<ul>
<li>If you get a Box2D error when running gym.make(‘LunarLander-v2’), you will have to compile Box2D from source. Please follow these steps and try running Lunar Lander again https://github.com/openai/ gym/issues/100:

pip uninstall box2d-py

<pre>     git clone https://github.com/pybox2d/pybox2d
     cd pybox2d/
     python setup.py clean
     python setup.py build
</pre>
<pre>     sudo python setup.py install
</pre>
</li>
<li>Windows users may install Box2D with the prebuilt Python wheels provided at https://www.lfd.uci. edu/~gohlke/pythonlibs/#pybox2d</li>
<li>Even if you don’t build an agent that solves the problem you can still write a solid paper.
1.6 Resources

1.6.1 Lectures

• Lesson 8: Generalization 1.6.2 Readings

• Chapter 9 (On-Policy Prediction with Approximation) of Sutton and Barto 2020
</li>
</ul>
1.7 Source Code

• https://github.com/openai/gym/blob/master/gym/envs/box2d/lunar_lander.py 1.7.1 Documentation

• http://gym.openai.com/docs/ 1.8 Submission Details

The due date is indicated on the Canvas page for this assignment. Make sure you have set your timezone in Canvas to ensure the deadline is accurate.

Due Date: Indicated as ”Due” on Canvas

Late Due Date [20 point penalty per day]: Indicated as ”Until” on Canvas

The submission consists of:

• Your written report in PDF format (Make sure to include the git hash of your last commit) • Your source code in your personal repository on Georgia Tech’s private GitHub

To complete the assignment, submit your written report to Project 2 under your Assignments on Canvas:

<pre>https://gatech.instructure.com
</pre>
You may submit the assignment as many times as you wish up to the due date, but, we will only consider your last submission for grading purposes. Late submissions will receive a cumulative 20 point penalty per day. That is, any projects submitted after midnight AOE on the due date get a 20 point penalty. Any projects submitted after midnight AOE the following day get a 40 point penalty and so on. No project will receive a score less than a zero no matter what the penalty. Any projects more than 4 days late and any unsubmitted projects will receive a 0.

Note: Late is late. It does not matter if you are 1 second, 1 minute, or 1 hour late. If Canvas marks your assignment as late, you will be penalized. Additionally, if you resubmit your project and your last submission is late, you will incur the penalty corresponding to the time of your last submission.

Finally, if you have received an exception from the Dean of Students for a personal or medical emergency we will consider accepting your project up to 7 days after the initial due date with no penalty. Students requiring more time should consider withdrawing from the course (if possible) or taking an incomplete for this semester as we will not be able to grade their project.

</div>
</div>
</div>
