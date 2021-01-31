<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/><img src="https://img.shields.io/badge/PyTorch%20-%23EE4C2C.svg?&style=for-the-badge&logo=PyTorch&logoColor=white" />

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/3ZadeSSG/Reinforcement-Learning-Agents/blob/main/LICENSE)

<img src="https://github.com/3ZadeSSG/Reinforcement-Learning-Agents/blob/master/Assets/unity_ml.png">
# Reinforcement Learning Agents
This repo contains two use cases where RL is used.
1. A robotic arm to reach an object
2. Playing tennis

Unity ML Agents environment have been used to train these agents using Reinforcement Learning for performing the task.

<img src="https://github.com/3ZadeSSG/Reinforcement-Learning-Agents/blob/master/Assets/robot.gif"><img src="https://github.com/3ZadeSSG/Reinforcement-Learning-Agents/blob/master/Assets/tennis.gif">

### Setup
1. Download the environment
    a. For Robotic Arm
    | Operating System  |  Link |
    | ------------- | ------------- |
    | Windows 64 Bit | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
    | Windows 32 Bit | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    | Linux | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    | Mac OS | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)

    b. For Tennis
    | Operating System  |  Link |
    | ------------- | ------------- |
    | Windows 64 Bit | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    | Windows 32 Bit | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    | Linux | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    | Mac OS | [Download](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)

2. Install Anaconda for creating virtual environment. [Link](https://www.anaconda.com/products/individual)
3. Install Python 3.6 in virtual environment
    ```
        conda create --name <env_name> python=3.6
        activate <env_name>
    ```
4. Install dependencies
    a. Run setup with
        ```pip install . ```
    b. Install pytorch from whl (version 0.4.x)  [Link](https://pytorch.org/get-started/previous-versions/#old-pytorch-linux-binaries-compiled-with-cuda-75)
        ```pip install <whl_link>```
        Example for Windows:
        ```pip install https://download.pytorch.org/whl/cpu/torch-0.4.1-cp36-cp36m-win_amd64.whl```


5. Create Kernel for Jupyter Notebook
    ```
        python -m ipykernel install --user --name <env_name> --display-name "<kernel_name>"
    ```
6. Run Jupyter Notebook
7. Change Kernet Type whenever running any of the Notebooks from either Tennis or Robotic Arm
        a. Select Kernel from Tab after opening the notebook
        b. Change Kernel
        c. Select "<kernel_name>"




