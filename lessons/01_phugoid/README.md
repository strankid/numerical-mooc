# Module 1: The phugoid model of glider flight.

## Summary

The phugoid model motivates the learning of numerical time integration methods. The model is described by a set of two nonlinear ordinary differential equations, representing the oscillatory trajectory of an aircraft subject to longitudinal perturbations.

* [Lesson 1](http://nbviewer.ipython.org/github/krajit/numerical-mooc/blob/master/lessons/01_phugoid/01_01_Phugoid_Theory.ipynb) presents the physics of phugoids in the assumption of zero drag (following Lanchester, 1909). Plotting the flight path gives fascinating curve shapes.

  [Lesson 1 - learning objectives](https://github.com/krajit/numerical-mooc/blob/master/lessons/01_phugoid/01_01_Phugoid_Theory_learningObjectives.ipynb)


* [Lesson 2](http://nbviewer.ipython.org/github/krajit/numerical-mooc/blob/master/lessons/01_phugoid/01_02_Phugoid_Oscillation.ipynb) develops a single-equation model for zero-drag oscillations, leading to simple harmonic motion. The lesson defines initial-value problems, demonstrates Euler's method, and uses the exact solution to study the numerical convergence. 
* [Lesson 3](http://nbviewer.ipython.org/github/krajit/numerical-mooc/blob/master/lessons/01_phugoid/01_03_PhugoidFullModel.ipynb) develops the full phugoid model and solves it with (vectorized) Euler's method. In the absence of an exact solution, the study of convergence uses a grid-refinement method, obtaining the observed order of convergence. The lesson ends with the paper-airplane challenge.
* [Lesson 4](http://nbviewer.ipython.org/github/krajit/numerical-mooc/blob/master/lessons/01_phugoid/01_04_Second_Order_Methods.ipynb) starts with the screencast "Euler's method is a first-order method" and develops second-order methods: explicit midpoint (modified Euler) and Runge-Kutta. It ends with a grid-refinement study.

### Category: 

Higher education, graduate

### Tags: 

engineering, computation, higher education, numericalmooc, python, snu, shiv nadar university, ajit kumar, github


[Course GitHub repo](https://github.com/krajit/numerical-mooc)
