We tried to implement the following paper and use the existing results and compare it to the main results in the paper.

The network is designed to identify the structural modal parameters from the vibration data of structures. 
The mixture signals, that is, the structural response data, are used as the input of the neural network. Then we use a complex loss function to restrict the training process of the neural network, making the output of the third layer the modal responses we want, and the weights of the last two layers are mode shapes.
The deep neural network is essentially a nonlinear objective function optimization problem. 
A A novel loss function is proposed to constrain the independent feature with consideration of uncorrelation and non-Gaussianity to restrict the designed neural network to obtain the structural modal parameters.
A numerical example of a simple structure and an example of actual SHM data from a cable-stayed bridge are presented to illustrate the modal parameter identification ability of the proposed approach. 

You can see the entire article from the link below

https://arxiv.org/pdf/2004.07644.pdf
