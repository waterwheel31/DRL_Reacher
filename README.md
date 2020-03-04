[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"



# Double Joint Arm Agent using a policy based method



## Environment Overview

This users [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]
(the image above has multiple robot arms, but in this repository, only one robot arm is implemented)

#### Conditions

A double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

#### Reward
- +0.1 for each step that the agent's hand is int goald location

#### State Space

- Continuous 33 dimensions corresponding to the arms':
    - positions
    - rotation
    - veclocity
    - angular veroties

#### Action Space
- Continuous 4 dimensions (torques of 2 joins of a robot arm)
- Each has range of [-1, 1]

## Goal of the agent 

- get an average score of more than +30  
- for 100 consecutive eposodes 

<hr>

## Algorithm 



## Performance

- 




## Ideas for Future Work

- Architecture: Currently, just used simple NN. Going forward, using more complex architecture may improve the score
- Hyperparameter: the parameter has not been fully optimized. Here is another opportunity of improvement


<hr>

## How to Run

- The trained model is `checkpoint.pth`. You can use this on Unity environment


## Dependencies

1. Download the Unity environment from one of the links below
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    

2. Place the file in this repository and unzip 
