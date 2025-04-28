# cs4246-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS4246 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs4246-semester-1-ay2022-23-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115592&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4246  Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
• IMPORTANT! Please write the following on the top of your solution files for EACH problem in the assignment:

– Name, metric number and Tutorial Group of all team members as they appear on LumiNUS

– Sources, if any, or if you obtained the solutions through research, e.g. through the web.

• Upload the code of your programming assignment to the aiVLE evaluation server, by following the instructions here. Please keep a copy of your submission zip file for safety.

• Please name your files, using ONE of the members’ information according to this format:

A1&lt;Member1-TutorialGroup&gt;-&lt;Member1-name&gt;-Task1 and A1&lt;Member1-TutorialGroup&gt;-&lt;Member1-name&gt;-Task2.

E.g., A1TG6-joycexiaomei.tan-Task1.zip and A1TG6-joycexiaomei.tan-Task2.zip

• A late score penalty of 20% will be incurred for late programming assignment solutions submissions.

1 Homework Assignment (LumiNUS Quiz)

1.1 Homework Problem 1: The Blocks World Reloaded

• There are only four objects in the world – Block A, Block B and the Table.

• Every block is on top of another object, i.e., On(x, y), where x is a block and y is another object.

• You can re-arrange a block by moving it to (the top of) another object, i.e., Move(x, fr, to), where x is a block, and fr, to are other objects in the world.

• You can move a block only when it is not stacked upon, i.e., it is “clear” on the top, or Clear(x), where x is a block.

• You cannot move the Table, but you can always move something to or from the Table, i.e., Clear(Table) is always assumed to be True (interpreted as: there is always “clear space” on the Table).

b. Show the search tree for planning by forward search.

c. Show the search tree for planning by backward search.

d. Show a valid plan for the problem.

1.2 Homework Problem 2: Programming as Planning

a. Write an action schema for the assignment operator (assigning the value of one variable to another). Remember that the original value will be overwritten!

b. Show how object creation can be used by a planner to produce a plan for exchanging the values of two variables by using a temporary variable.

2 Programming Assignment (aiVLE submission)

In this assignment, we will learn to generate the PDDL description files which will be used to solve 2 different planning problems. Before proceeding further, follow the instructions below to complete the setup required for this programming assignment.

Installation Instructions

• Setup docker on your machine, instructions for which can be found here.

• Pull the docker that we have already setup for you with all the required dependencies. You can follow the instructions here to do so.

• After pulling the docker image, test your your installation by running

docker run -it –rm -v $PWD:/workspace cs4246/base python test_installation.py for Linux/Mac or

docker run -it –rm -v %(cd)%:/workspace cs4246/base

python test_installation.py for Windows (file given along with this assignment) on the docker container.

Programming Assignment Submission Instructions

Please follow the instructions listed here. Task specific submission instructions are as follows:

a. For Task 1 : You have been provided with a .zip file in the correct submission format. Complete the functions marked with “FILL ME” in __init__.py. Your submission zip file should have the exact same structure as the zip file you received.

b. For Task 2 : Modify the __init__.py as required and make a separate submission. You can add code out of ”FILL ME” block and even edit some code in the template if needed.

Note :

• Please do not print anything to the console, as it might interfere with the grading script.

Getting started

We will be using the gym grid environment to simulate the solution obtained on feeding the PDDL files generated to a planner. These dependencies have been installed in the docker image “cs4246/base” which you have downloaded.

Read through the introduction and example from Pellierd/pddl4j tutorial to understand the PDDL description format. You can look at sample problem and domain files for further understanding. If you want to, you can also feed any problem and domain PDDL files to a planner by running the following command on the docker container (using the docker run … command):

/fast_downward/fast-downward.py domain.pddl problem.pddl –search “lazy_greedy([ff()], preferred=[ff()])” Note that in this PDDL format, specifying negative literals in preconditions is allowed.

For you to get used to the PDDL format, we have prepared a sample python script to generate PDDL files for the Air Cargo problem. You can run the file pddl_cargo_example.py (using the docker run … command)] to see the PDDL files generated cargodomain.pddl, cargoproblem.pddl and also relevant portions of the code that generates it. Specifically, it will be helpful to look at functions :

1. generateDomainPDDLFile(),

2. generateProblemPDDLFile()

3. generateInitString()

4. generateGoalString()

You are now ready to begin solving the two tasks which are listed below! We use the PDDL description format mentioned here.

2.1 Programming problem 1: Parking Task

By virtue of being a Computing student, you decide to put your planning skills to use. You first retrieve an old python script written for a similar task by the TAs of CS4246/CS5446, parts of which have been lost. The script used to generate the PDDL files and fed them to the fastdownward solver to generate a solution for this planning problem. It also runs the plan on the simulator to see if it does the job.

The script python __init__.py is missing 3 code snippets (marked with “FILL ME” in the file) .

1. Code which generates the action schemas of the three actions available namely, UP, DOWN and FORWARD. These action schemas should reflect the 3 actions available in the environment simulator. The agent’s speed range in the environment is restricted to [-1, -1] (negative speed moves towards the left, see the environment for more details).

2. Code which generates the initial state condition.

3. Code which generates the goal description.

You can test your code with the test configurations given in the script by running python __init__.py parking N (present in the .zip file) , where N is an int value between 0 to 5, on the docker (using the docker run … command). It might be helpful to look at the generated PDDL files for debugging.

2.2 Programming problem 2: Crossing the road

You decide to modify the script you wrote in Task 1 to handle this situation. You can test your code by running python __init__.py crossing 0 in command with docker

Hint: Instead of modeling the parking lot/road as a 2 dimensional grid, it might be useful to include time as an additional dimension.
