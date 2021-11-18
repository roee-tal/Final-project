# Ex1 - the elevator mission - offline algorithm
![This is an image](https://www.pexels.com/photo/modern-geometric-building-with-moving-elevators-6249432/)
#### ID of presenters: 315858506,316156108

### Table of contents:
* Sources(Literature survey)
* Problem space
* Classes structure
* Algorithm's principle
* Algorithm structure
* Class diagram
* Results


###  Sources(Literature survey):
[Source #1](https://softwareengineering.stackexchange.com/questions/331692/what-algorithm-is-used-by-elevators-to-find-the-shortest-path-to-travel-floor-or) - great answers to cut the total waiting times.

[Source #2](https://www.cs.huji.ac.il/~ai/projects/2014/The_intelevator/files/report.pdf) - 
quality job which explaines the principle's of the elevator's movement and gave us good inspiration.

[Source #3](https://www.i-programmer.info/programmer-puzzles/203-sharpen-your-coding-skills/4561-sharpen-your-coding-skills-elevator-puzzle.html?start=1) - also good principle's of the elevator's movement and emphasis to weak point on designing elevator's movement.


### Problem space:
We will notice that unlike the online situation, which there the calls are not given and we have no idea about the call details before it called, in the offline situation the whole calls are given to us, we have more data to work with. Therefore, the decision making can conider future data, so the calculate might be more complicated. Moreover, the position of the elevator are not given to us, which means we had to calculate good estimate about the position. Also, in this project we worked with files as json, so we had 'to exchange' in a good way the 'keys' to fiels into the classes that we create so we can use them.


### Classes structure:
* data class - **Manage**- which manage the calls and the position of the elevators.
* Because we want to get accsess to the data in order to send the elevators in the optimal situation, we create class which manage the calls, when every elevator has it's own call list. This class serving the main algorithm class, giving call list in real time, position and more.
* algorithm class - **Offline**- which alocate every call in real time, and finally write the results to output file.
* Building class - **Building**- which recives the data from the json file and put it into the fitting fiels, and serving the offline class.
* Elevator class - **Elevator**- which recives the data from the json file and put it into the fitting fiels, and serving the offline class.
* Call class - **Calls**- which recives the data from the csv file and put it into the fitting fiels, and serving the offline class.


### Algorithm's principle:
Every time



### Class diagram


