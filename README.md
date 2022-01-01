***
## Hands-on Reinforcement learning
***
The repo provides you with solutions for multiple OpenAI environments using classical reinforcement learning methods. 
So far, the Taxi-v3 and the MountainCar-v0 solutions are added.

|Environmet| Algorithm | Model-based | Link|
|:---------:|:-----------:|:-------------:|:---:|
|Taxi-v3   | SARSA      |  No | [link](https://github.com/alirezahss88/Reinforcement-Learning-/blob/master/Taxi%20v3%20with%20SARSA%20algorithm.ipynb) |
|MountainCar-v0| Q-learning|No| [link](https://github.com/alirezahss88/Reinforcement-Learning-/blob/master/MountainCar-v0%20with%20Q-learning.ipynb) |

To train each model, you will need to make an instance of the class and call for the *train* method. For example:
```
taxi = Taxi3(env, n_epochs)
taxi.train()
```
To test the trained model, call for the *test* method i.e.
```
taxi.test()
```


**Pre-requisits:**

You need to have a concrete knowledge of Reinforcement Learning and the Python programming language specifically OOP.

Also, You need to have installed the following packages before starting running the code.

- [Python 3.6 or 3.7](https://www.python.org/downloads/release/python-360/) 

- OpenAI gym
```
pip install gym            #command prompt
!pip install gym           #Jupyter Notebook
```
To instantiate the environment, you need use the code below and repalce the *environment_name* with the name from the table above:
```
env = gym.make('environment_name')
```
- Numpy
```
pip install numpy            #command prompt
!pip install numpy           #Jupyter Notebook
```
- Pyglet
```
pip install pyglet            #command prompt
!pip install pyglet           #Jupyter Notebook
```
