# CPSC571

This is a term project that aims to compare a simple methodology with existing machine learning methods for League of Legends Match Prediction Accuracy.

In this project we aim to use the riot API for all the match data collection and Python + MongoDB for our project core tech stack.

## Steps to set up the project in the environment
* Make sure you have ```pip``` install on your computer.
* Install Jupyter Lab using the command ```pip install jupyterlab```.
* Run jupyter lab by opening a new command prompt and typing ```jupyter lab```. If the terminal throws an error, use this video to fix it https://www.youtube.com/watch?v=FZoDIwe1_YM
* Install pymongo in your computer ```pip install pymongo```
* Install requests in your computer (as we need this to go back and forth with RIOT Api) ```pip install pymongo``

After all the steps above have been set up.
You have the ability to access 2 files which have code: 
1. Riot.ipynb - This file has the code which is very static, we only analyse the games of one random person from the Riot API and use that to set up our code initially.
2. LoopRiotApi.ipynb - This file contains the main code which is dynamic and has the ability to take in account thousands of games at a single time and the user does not have to worry about the limitations of the code. 

** Both the files above contain detailed explanaition of the code (in-line comments) which would help someone who is new to understand how Riot API works and how to connect MongoDB to their python project. ** 
