# Solving Partial Differential Equations

In a previous repository (see the [README](https://github.com/jescott07/solving-ordinary-differential-equations/blob/main/README.md)) we saw what an ordinary differential equation (ODE) is and some methods to solve them, so we applied these methods to some examples. Now, we wana study a different tipy of a differental equation, the partial differential equation (PDE). In the introduction we will discuss more about an EDP, them we will show three different methods to solve them in subsequent sections.

## Introduction

In a ODE we have an equation wich the derivatives are taken with respect to only one variable, in an PDE however the equation depends on partial derivatives of several variables, for example, the heat equation:

<p align='center'>
$\frac{\partial u}{\partial t} = \frac{\partial ^2 u}{\partial x^2}$
<p/>

is an PDE. In physics we have several applications of a PDE such as: The diffusion equation that describes the density fluctuation of a material that diffuses; The wave equation that is mostly used in classical and quantum mechanics and the Maxwell's equations that describe an electromagnetic wave. Therefore, it is important to know more about them and how we can solve them.
