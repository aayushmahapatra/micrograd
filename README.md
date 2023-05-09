# micrograd

This project is a tiny **Autograd engine**, designed to implement backpropagation (reverse-mode autodiff) over a dynamically built 
Directed Acyclic Graph (DAG). It also includes a small **neural networks library** built on top of the Autograd engine, providing a 
**PyTorch-like API**. Both are of small size, the Autograd engine consists of approximately 100 lines of code, while the neural networks 
library comprises around 50 lines of code.

## Features
- **Autograd Engine:** The Autograd engine is capable of performing reverse-mode autodiff over a dynamically constructed DAG.
- **Neural Networks Library:** The library provides a small yet powerful neural networks framework built on top of the Autograd engine.
- **PyTorch-like API:** The neural networks library offers an intuitive API inspired by PyTorch, making it easy to use and understand.

## Acknowledgments
This project is based on the work by **Andrej Karpathy** and is adapted from his GitHub repository. 
I express my gratitude to **Andrej Karpathy** for his pioneering contributions in the field of deep learning, 
and for making this project available to the community.
