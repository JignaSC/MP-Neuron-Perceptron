# MP-Neuron-Perceptron
Classification of brest cancer data with the help of MP Neuron and Perceptron

## MP Neuron ##
![MP Neuron](https://miro.medium.com/max/554/1*fDHlg9iNo0LLK4czQqqO9A.png)\
The first computational model of a neuron was proposed by Warren MuCulloch (neuroscientist) and Walter Pitts (logician) in 1943.\
It may be divided into 2 parts. The first part, g takes an input (ahem dendrite ahem), performs an aggregation and based on the aggregated value the second part, f makes a decision.\
![](https://miro.medium.com/max/825/1*NLchBzohJvCCNMPPnF-V-A.png)

### Limitations of MP Neuron ###
* What about non-boolean (say, real) inputs?
* Do we always need to hand code the threshold?
* Are all inputs equal? What if we want to assign more importance to some inputs?
* What about functions which are not linearly separable? Say XOR function.

## Perceptron ##
Perceptron is a single layer neural network and a multi-layer perceptron is called Neural Networks.\
Perceptron is usually used to classify the data into two parts. Therefore, it is also known as a Linear Binary Classifier.\
![Perceptron](https://miro.medium.com/max/624/1*gS9pPUg1n537rlzicA_UlA.png)

### Limitations of Perceptron ###
* Can classify Linearly seperable data.
