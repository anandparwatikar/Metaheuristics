# Metaheuristics
Materials posted here are for academic and experimental puposes ( Subject : Metaheuristics and Optimization )

The objective of this exam is to solve different problems using metaheuristics. You will have
2 discrete optimization problems and 6 continuous problems to solve.

For each function you are expected to report:
- The chosen algorithm and a justification of this choice
- The parameters of the algorithm
- The final results, both solution and fitness
- The number of function evaluations
- The stopping criterion
- The computational time
- The convergence curve (fitness as a function of time)

# Requirements
Codes should be provided in Python and published on a public Github repository with a
folder for each function. A readme.md should be also there describing the required criteria
as well as a description on how to execute the code to reproduce the final results.

# Discrete optimization:
You will have to solve the two TSP problems.
One with 38 cities (Djibouti) and the other with 194 cities (Qatar)
Data (in TSPLIB format) can be found on the following link:
http://www.math.uwaterloo.ca/tsp/world/countries.html
As a recall, your aim is to find the shortest path, so you visit all cities without visiting the
same twice.

# Continuous optimization:
You will have to optimize the 6 first functions 6 Functions (F1-F6). The description of the first
6 functions are available in the “CEC2008_TechnicalReport.pdf”. You should provide results
for both dimension D = 50 and D = 500.
F1: Shifted Sphere Function
F2 : Shifted Schwefel’s Problem 2.21
F3 : Shifted Rosenbrock’s Function
F4 : Shifted Rastrigin’s Function
F5 : Shifted Griewank’s Function
F6 : Shifted Ackley’s Function
The code of the functions as well as the shifts are available in cec08.rar (in C)
