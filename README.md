### Udacity Machine Learning Engineer Nanodegree
# Capstone Project – Robot Motion Planning
## Plot and Navigate a Virtual Maze

### Description
This project is inspired from an event ‘Micromouse Competitions’ where a small robot navigates a maze and learns the shortest path to the center of that maze. The competition originated in the 1970s and is a popular event held around the globe. The project deals with the basic concepts of motion planning in artificial intelligence and is an attempt to apply machine learning in the field of autonomous robotics. 
The mazes to be used in this project is provided on the Udacity Project Page in the form of text files along with some starter code files. The source of the files is provided through this link. These are the samples mazes provided by Udacity to test the robot.

### Project Requirements
* Python 3.6
* Numpy
### Files
* robot.py - This script establishes the robot class. 
* maze.py - This script contains functions for constructing the maze and for checking for
                 walls upon robot movement or sensing.
* tester.py - This script will be run to test the robot’s ability to navigate mazes.
* showmaze.py - This script can be used to create a visual demonstration of what a maze
                         looks like.
* mazes – Folder containing four maze files upon which to test the robot. Files are named 
               as test_maze_##.txt . The ## is to be replaced by 01, 02, 03 & 04.
* Capstone report : Documentation for the whole project
* Capstone Proposal : Capstone proposal for this project

### To run the tester:
python tester.py mazes\test_maze_01.txt

### To visualize the maze:
python showmaze.py mazes\test_maze_01.txt
