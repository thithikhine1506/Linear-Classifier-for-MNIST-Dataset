# Linear-Classifier-for-MNIST-Dataset
MNIST is a standard digit classification dataset. Given a 28 ×28 image containing a digit from 0 to 9, our goal is to deduce which digit the image corresponds to. The dataset has 60,000 training and 10,000 test examples. 

**Linear Classifier for MNIST: From Scratch vs. PyTorch**

**Project Overview**
The core of this project is a manual implementation of Minibatch Stochastic Gradient Descent (SGD). Instead of relying solely on high-level frameworks, I derived and coded the forward pass, loss functions, and gradient updates using NumPy to deeply understand the mathematical foundations of neural networks.

**Key Technical Features**

**Mathematical Foundation**: Implemented quadratic loss with L2 regularization.

**Custom SGD**: Built a robust training loop featuring one-hot encoding, weight initialization, and minibatch selection.

**Vectorized Implementation**: Optimized the forward pass and gradient calculations using matrix operations for efficiency.

**Framework Verification**: Validated the scratch implementation against PyTorch, achieving nearly identical loss convergence.

**Tech Stack**

Language : Python

Libraries : NumPy, Matplotlib (Visualization), PyTorch (Verification), Torchvisio
