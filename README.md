Feed Forward Neural Network
===========================

This project is aims to be a clean reference implementation of artificial
neural networks in Python 3 under the MIT license. It's part of my efforts to
understand the concepts of deep learning.

You can use this repository when doing your own implementation of neural
networks which I highly recommend if you are interested in understanding them.
It makes sure you correctly understand all the details. For example, I had a
small misunderstanding of the backpropagation formula. My network still trained
but I found the mistake by numerical gradient checking.

Instructions
------------

If you have Numpy and Matplotlib for Python 3 installed on your machine, you
can just run this command. To tweak parameters of the networks like changing
activation functions or number of layers just edit the last section of this
file.

```bash
python3 ffnn.py
```

Features
--------

This repository provides implementations for a layered neural network,
activation functions, cost functions and different optimization algorithms. All
those are implemented in an object-oriented design so that alternatives can be
added easily. There are also two generated toy problems for the networks to
learn.

### Activation functions

| Function | Definition | Graph |
| -------- | :--------: | ----- |
| Linear | x | ![Linear activation](image/linear.png) |
| Sigmoid or logistic | 1 / (1 + exp(-x)) | ![Sigmoid activation](image/sigmoid.png) |
| Relu | max(0, x) | ![Relu activation](image/relu.png) |

### Cost functions

| Function | Definition | Graph |
| -------- | :--------: | ----- |
| Squared | 1 / 2 * (prediction - target) ^ 2 | ![Square cost](image/squared.png) |

### Optimization algorithms

- Stochastic gradient decent
- Batch gradient decent
- Mini batch gradient decent

### Gradient algorithms

- Backpropagation
- Numerical gradient
- Checked gradient

Contribution
------------

Feel free to file pull requests. If you have questions, you can ask me.