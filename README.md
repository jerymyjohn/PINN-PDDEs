# Physics-Informed Neural Networks for Proportional Delay Differential Equations (PINN-PDDEs)

## Introduction

This repository contains the implementation of Physics-Informed Neural Networks for Proportional Delay Differential Equations (PINN-PDDEs) – a deep neural network framework designed to solve both forward and inverse problems related to proportional delay differential equations (PDDEs). This approach integrates proportional delay differential equations into neural networks, enabling the accommodation of diverse requirements such as initial conditions, control equations, and known data.

## Environment Configuration

This project was developed using Baidu's PaddlePaddle AI Studio with the following configuration:

- **GPU**: Tesla V100
- **Video Memory**: 32GB
- **CPU**: 4 Cores
- **RAM**: 32GB
- **Disk**: 100GB

You can use the following link to access Baidu's PaddlePaddle AI Studio.

 ![Static Badge](https://img.shields.io/badge/Baidu-AI_Studio-brightgreen?style=plastic&logo=baidu&link=https%3A%2F%2Faistudio.baidu.com%2Findex)

## Installation

**Clone the repository:**

```
git clone https://github.com/HousenWang/NDDEs.git
cd NDDEs
```

**Install required packages:**

To ensure your environment is fully compatible with this project, you can download a pre-packaged set of all required libraries from the link below. This file contains all necessary dependencies as they were configured and used in the development environment.

[Download Packaged Dependencies](https://drive.google.com/file/d/1aZzYxiEs0ugrfa6piFoQye_fBNg3tsWJ/view?usp=sharing "Download dependencies")

## Code

The code for our numerical experiments can be found in the [`work`](https://github.com/HousenWang/NDDEs/tree/master/work) directory.
