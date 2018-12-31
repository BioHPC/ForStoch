# ForStoch
FORTRAN software suite for Stochastic Simulation of Biochemical Kinetics especially for Cell Cycle Model

The stochastic simulation algorithm (SSA), proposed by Gillespie, is a cardinal simulation method for the chemical kinetics. Because the SSA simulates every reaction event, the amount of the computational time is huge when models have many reaction channels and species.This drawback motivates many attempts to improve the efficiency with the accuracy.The ForStoch includes orignial Gillespie SSA and other approximation algorithms. You can run very simply the algorithms with several test case systems.

The algorithms:

1) Gillespie SSA
2) Explicit tau-leaping
3) Implicit tau-leaping
4) Trapezoidal tau-leaping
5) Fully implicit BE-BE
6) Fully implicit TR-TR
7) Fully implicit BE-TR
8) Implicit second order weak Taylor method with alpha=1.0 and beta=1.0
9) Implicit second order weak Taylor method with alpha=1.0 and beta=0.0
10) Implicit second order weak Taylor method with alpha=0.5
