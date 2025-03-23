Objective
The goal of this project is to compare the performance of two optimization algorithms — Harris Hawks Optimization (HHO) and Aquila Optimizer (AO) — on two well-known mathematical functions:

Matyas Function – A unimodal function with a global minimum at (0,0).
Sphere Function – A simple convex function commonly used as a benchmark for optimization algorithms.
Convex and simple structure, often used to test convergence.
Optimization Algorithms
Harris Hawks Optimization (HHO):
Inspired by the cooperative behavior of Harris hawks when hunting prey.
Balances exploration (searching for prey) and exploitation (attacking the prey).
The algorithm updates positions of hawks based on random movements around the best solution.
Aquila Optimizer (AO):
Inspired by the hunting strategy of the Aquila eagle.
Combines searching and attacking strategies with random walk movements.
Balances between global search (exploration) and local search (exploitation).
Project Workflow
Define Mathematical Functions
Define the Matyas and Sphere functions.
Define Optimization Algorithms
Implement HHO and AO algorithms using Python classes.
Initialize agents in a multidimensional search space.
Update positions based on algorithm-specific rules and update best-known solution.
Perform Optimization
Run HHO and AO on both Matyas and Sphere functions.
Track the convergence process over iterations.
Results and Comparison
Plot convergence graphs to visualize performance over iterations.
Generate a 3D plot of the two functions.
Compare best scores from both algorithms for each function.
Display Results
Display the results in a table format using the tabulate library.
Print the winner algorithm based on the best score.
Technologies and Tools
✅ Python
✅ NumPy
✅ Matplotlib
✅ Tabulate
✅ Pandas
✅ Scikit-learn

Insights
The HHO and AO algorithms both converged quickly, but the performance varied between the two functions.
HHO showed better performance on the Sphere function due to its faster exploration and exploitation balance.
AO showed competitive results on the Matyas function, demonstrating strong local search ability.
Next Steps
🔎 Test on more complex functions (e.g., Rastrigin, Rosenbrock).
🔎 Tune hyperparameters such as population size and maximum iterations.
🔎 Try hybrid models combining HHO and AO strategies.







