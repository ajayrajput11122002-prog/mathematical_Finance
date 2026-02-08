## Monte Carlo Expectation of a Random Variable

### Mathematical Setup
Let X ~ N(0,1)

Theoretical results:
- E[X] = 0
- Var(X) = 1

### Objective
Use Monte Carlo simulation to verify the theoretical expectation and variance.

### Method
- Generate i.i.d. samples from N(0,1)
- Estimate expectation using sample mean
- Estimate variance using sample variance

### Results
As the number of samples increases, Monte Carlo estimates converge to theoretical values.

### Assumptions
- Independent samples
- Pseudo-random number generator approximates true randomness

### Limitations
- Monte Carlo error decreases at rate O(1/√N)
- Finite-sample approximation

### Extensions
- Other distributions
- Conditional expectation
- Law of Large Numbers simulation
