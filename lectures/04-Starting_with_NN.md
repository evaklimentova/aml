## Starting with Neural Networks

### Required Study Materials

StatQuest series about NNs: <https://www.youtube.com/watch?v=CqOfi41LfDw>, <https://www.youtube.com/watch?v=IN2XmBhILt4>, <https://www.youtube.com/watch?v=68BZ5f7P94E>, <https://www.youtube.com/watch?v=83LYR-1IcjA>

Alternative series - first three parts, they can replace 'inside the box + backpropagation main ideas': <https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi>

### Activities

#### 1. Backpropagation

- we have a small neural network that should compute from two equations the value of two unknotwns, *x* and *y*
- we initialized it with some weights and biases, but it doesn't predict the results well
- we will have one training sample, at first do the forward pass
- then train the last layer of the network, use gradient decent with backpropagation, doc first weight and bias together
- do again forward pass and see if the predictions are better
- we can iterate this (just guess the numbers and not compute them precisely)
- [supporting script](04_simple_network_training.ipynb) for this exercise

#### 2. Power of one neuron - logic gates

- try to set weights and bias for one neuron with [unit step activation function](https://www.researchgate.net/profile/Raghad-Salih/publication/320612982/figure/fig1/AS:680085346586634@1539156390523/Figure-1-Unit-step-function.png) so it behaves as NOT (one input), AND, OR (two or if enough time multiple inputs) and XOR
- think about interpretation of the neuron in space (-> line splitting the space into halves), why XOR does not work?
- try to make a bigger NN for XOR, possibly by combining previous logic gates

### Project

- think about groups for project and their tasks

### Reasoning

- dive into Neural Networks, get some intuition behind
- at least intuitively understand how backpropagation works
- show that NNs are very powerful
