APC523 Final Project

Solvers for the Vlasov equation.

This repository contains slides, a Jupyter notebook titled "Vlasov Solver Notebook",  a Jupyter notebook titled "Numerical Experiments," and a writeup on the methods.

The write-up includes a brief introduction to the Vlasov equation(s) and important physical tests. The write-up then presents a first-order method along with the stability, modified equation, accuracy, and positivity analysis of the method.
A second-order method is then presented along with stability, accuracy, and modified equation analysis. Finally, slope limiters are introduced, and the positivity of the slope-limited, second-order methods are discussed. 
We finish the report by running some numerical experiments comparing the compute-time and accuracy of the different Vlasov solvers against the resolution of the simulation. 

The Vlasov Solver Notebook contains all the code for the methods and contains simulations/physical verifications for all the methods. In particular, physically accurate simulations of plasma oscillations and the two-stream instability are present. 
Tests of the solvers with a prescribed Hamiltonian are also presented. The expected behaviors of the numerical schemes are verified. The Jupyter notebook is already compiled, but can also be run on Adroit by downloading the file.

The file "Numerical Experiments" contains the code for the numerical experiments in the write-up. It is already compiled but can be run on Adroit.
