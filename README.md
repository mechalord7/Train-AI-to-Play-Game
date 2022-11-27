# Train AI to play Game

## Team 03
| Name                | SRN           |
| ------------------- | ------------- |
| Arunvenkat C A      | PES2UG20CS068 |
| Ashutosh Routray    | PES2UG20CS072 |
| C V Eswar Sai Reddy | PES2UG20CS096 |

##### We are using Reinforcement learning to train an agent to play a game. 

##### The game environments are taken from OpenAI Gym. 

#### Requirements of the project are mentioned below

```
gym==0.21.0
gym_super_mario_bros==7.3.0
ipython==8.6.0
matplotlib==3.4.3
nes_py==8.2.1
numpy==1.22.4
scikit_learn==1.1.3
stable_baselines3==1.6.2
```

The packages required to run the code can be installed by running the following command in the project's folder:

```
pip install -r requirements.txt
```

Note: Additional installations may be required along with the requirements mentioned above. Uncomment the contents of first cell in the file *Mario.ipynb*.

#### The project contanis three main files:

1. **qlearning.ipynb**
   Shows the implementation of Q-Learning Algorithm by applying the algorithm to play a game from OpenAI Gym

2. **Snake.ipynb**
   Shows the process of training a custom made game built on top of OpenAI Gym. The game state is given as input to the model

3. **Mario.ipynb**
   Shows the process of training a PPO model using CNNPolicy. Game frames are given as input to the model.

#### The project contains two additional files:

1. **demo_gym.ipynb**
   Shows a sample game in OpenAI Gym environment

2. **MarioModelRun.ipynb**
   Loads the model obtained after training for one million iterations and shows the sample gameplay of the trained model
   Note: The weights file (best_model_1000000.zip) is not uploaded along with the code files as it exceeds the maximum size limit. The file can be downloaded from [here](https://drive.google.com/drive/folders/1XSwF8hUQDotBrp9nL7LAmBstoQk0eXk7?usp=share_link)

* all files can be executed by running all cells in the notebooks by choosing the `run all` option in the notebook.  