# Snakes and Sirens: Can Sines Help Deep Learning?

This seminar is about the use of the _sine_ activation function and the introduction of inductive biases in Deep Learning. It reviews mainly the following two papers:

* Neural Networks Fail to Learn Periodic Functions
and How to Fix It: [Arxiv](https://arxiv.org/abs/2006.08195)


> Previous literature offers limited clues on how to learn a periodic function using modern neural networks. We start with a study of the extrapolation properties of neural networks; we prove and demonstrate experimentally that the standard activations functions, such as ReLU, tanh, sigmoid, along with their variants, all fail to learn to extrapolate simple periodic functions. We hypothesize that this is due to their lack of a "periodic" inductive bias. As a fix of this problem, we propose a new activation, namely, x+sin2(x), which achieves the desired periodic inductive bias to learn a periodic function while maintaining a favorable optimization property of the ReLU-based activations. Experimentally, we apply the proposed method to temperature and financial data prediction.

* Implicit Neural Representations with Periodic Activation Functions: [Arxiv](https://arxiv.org/abs/2006.09661)

> Implicitly defined, continuous, differentiable signal representations parameterized by neural networks have emerged as a powerful paradigm, offering many possible benefits over conventional representations. However, current network architectures for such implicit neural representations are incapable of modeling signals with fine detail, and fail to represent a signal's spatial and temporal derivatives, despite the fact that these are essential to many physical signals defined implicitly as the solution to partial differential equations. We propose to leverage periodic activation functions for implicit neural representations and demonstrate that these networks, dubbed sinusoidal representation networks or Sirens, are ideally suited for representing complex natural signals and their derivatives. We analyze Siren activation statistics to propose a principled initialization scheme and demonstrate the representation of images, wavefields, video, sound, and their derivatives. Further, we show how Sirens can be leveraged to solve challenging boundary value problems, such as particular Eikonal equations (yielding signed distance functions), the Poisson equation, and the Helmholtz and wave equations. Lastly, we combine Sirens with hypernetworks to learn priors over the space of Siren functions.

## Overview of Activation Functions
<p align="center">
  <img src="https://github.com/Juju-botu/silab/blob/master/seminar-1/images/screenshot_0.png" width=1000  alt="SILAB logo">
</p>

## Comparison of Snake and SIREN
<p align="center">
  <img src="https://github.com/Juju-botu/silab/blob/master/seminar-1/images/screenshot_1.png" width=1000  alt="SILAB logo">
</p>

