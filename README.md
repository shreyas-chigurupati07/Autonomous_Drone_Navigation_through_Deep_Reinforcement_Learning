# Drone Navigation with Deep Reinforcement Learning in AirSim

## Project Overview

This project implements a Deep Q-Network (DQN) to autonomously navigate drones in complex environments using the AirSim simulation environment. The goal is to demonstrate how reinforcement learning can be applied to real-world drone navigation challenges.

## Features

**Reinforcement Learning:** Uses a DQN model to handle decision-making in navigating through simulated environments.\
**Unreal Engine and AirSim Simulation:** Leverages the Unreal Engine and AirSim simulation environment to provide a realistic and versatile testing ground for autonomous drone behaviors.\
Customizable Training Scenarios: Includes settings to adjust the complexity and parameters of the training environments.


## Prerequisites
Python 3.8 or higher\
AirSim\
OpenAI Gym\
**Note:** Check the **requirements.txt** file for all the dependencies

## Setup
To run the code use following instructions.
1. Unzip the custom block environment and source code repo.
2. Lauch custom environment- RBE595_V2\WindowsNoEditor\Blocks
3. cd .\AirSim-main\PythonClient\reinforcement_learning\
4. To train the mdoel use following cmd,  'python .\dqn_drone.py'
5. To run the inference on saved checkpoint use following cmd, 'python .\dqn_inf.py'\


## Output

### Demo Videos
View the demo videos: 

<div align="center">
    <video src="Output/1.mp4" alt="Demo 1" width="30%"/>
    <video src="Output/2.mp4" alt="Demo 2" width="30%"/>
    <video src="Output/1.mp4" alt="Demo 3" width="30%"/>
</div>





## Contributors
Sujit Mohite

