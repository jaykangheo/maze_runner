# `maze runner`: A customizable framework to create maze and solve.

This repository contains a customizable framework to create maze and solve it.The motivation of this
repository is to provide users to enjoy how a robot would solve a maze based on randomly customized mazes. 

The repo will be actively maintained, any comments, feedbacks or improvements are highly welcomed. 

# Installation

## Install dependencies
Run the following command to install [all required dependencies](requirements.txt):

```bash
pip install -r requirements.txt
```

## Play with a maze

This project was tested on both MacOS and Windows. When starting the project, put Cozmo at the entrance, then go to the directory of this project. Disable comment the cozmo.run_program(solve_simple_maze) in python file called drive_cozmo.py. When solving hard maze, place cozmo in center of a white lane with black background and  disable comment the cozmo.run_program(solve_hard_maze) after commenting out cozmo.run_program(solve_simple_maze) under drive_cozmo.py.



