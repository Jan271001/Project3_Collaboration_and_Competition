# Report

## The result

![Plot of rewards](CPictures/Performace.png)

## The algorithm

For this project I used the MADDPG-Algorithm (Multi Agent Deep Deterministic Policy Gradient)

### Overall description

In order to fullfill the task I use a multi-agent-actor-critic approach.

### Net Architecture

### Actor

The actor-network is a simple feed-forward network

>Input Layer: 24 Nodes (state size)

>First Hidden Layer (ReLu): 128 Nodes

>Batch-Normalization-Layer

>Second Hidden Layer (ReLu): 128 Nodes

>Output Layer (tanh): 2 Nodes (action size)

### Critic

The critic-network is a simple feed-forward network

>Input Layer: 28 Nodes (state size + actions of both agents)

>First Hidden Layer (ReLu): 128 Nodes

>Batch-Normalization-Layer

>Second Hidden Layer (ReLu): 128 Nodes

>Output Layer (tanh): 1 Node

### Hyperparameters

>Learning Rate (Actor):   1e-4

>Learning Rate (Critic):  5e-3

>Discount Rate:           0.995

>Noise Decay:             0.999

>Softupdate Rate:         1e-3

>Random Seed:             1

### Pseudo-Code

In pseudocode the MADDPG-Algorithm looks like following:

![Pseudo-Code-MADDPG](Pseudo_Code_MADDPG.png)

## Annotation



## Future Ideas

Although the result with this algorithm fullfill all necessary requirements, there are a few more things I like to try. At first I want to know what the maximum for this Code is. So I like to adjust the hyperparameters network-architectueres and give it some more trys. Additionaly I like to try Prioritized Experience Replays, witch could improve the learning effects gained from previous interactions.
