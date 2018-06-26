# Machine Learning Engineer Nanodegree
# Reinforcement Learning
## Project: Train a Smartcab How to Drive

### Dependencies/Prerequisites

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed along with the Gym library.  Also requires sklearn for use of training machine learning algorithms.

### Installing

A step by step series of examples that tell you how to get a development env running

```
Verify sklearn and jupyter notebook are installed.
```

```
Go to the directory of the program.
```

```
Type 'jupyter notebook' on the command line for the given directory.
```

```
Make sure 'Python 3' is selected.
```

```
Run line by line.
```

After running each line, you'll see outputs below each line whether from status checks or output of regression equations.

### Description

Project gives a good demonstration on using Deep-Q learning for training a Smartcab to navigate cars and obstacles on a roadway.  The object is to replicate training used on self-driving cars.

### Code

Template code is provided in the `smartcab/agent.py` python file. Additional supporting python code can be found in `smartcab/enviroment.py`, `smartcab/planner.py`, and `smartcab/simulator.py`. Supporting images for the graphical user interface can be found in the `images` folder. While some code has already been implemented to get you started, you will need to implement additional functionality for the `LearningAgent` class in `agent.py` when requested to successfully complete the project. 

### Usage

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```

This will run the `agent.py` file and execute your agent code.

### Known Issues

None at this time.

### Future Planes

None at this time

### Contribution guidelines

Please refer to each project's style guidelines and guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

Fork the repo on GitHub
Clone the project to your own machine
Commit changes to your own branch
Push your work back up to your fork
Submit a Pull request so that we can review your changes
NOTE: Be sure to merge the latest from "upstream" before making a pull request!

### License

Project is open sourced under the Apache 2.0 license.
