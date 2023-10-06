# Poisson Probability Mass Function (PMF) Calculator

This Python code calculates and plots the Probability Mass Function (PMF) for a Poisson distribution. It allows you to specify the number of events (k) and the rate at which the events occur (lambda).

## Code Description

The code consists of a Python function called `poisson_pmf(k, lambda_val)` that takes two parameters:

1. `k`: Number of events to occur at the same time.
2. `lambda_val`: Lambda value, which represents the rate at which the events occur.

The function performs the following tasks:

1. Calculates the Poisson PMF for a given `k` and `lambda_val`.
2. Prints out the probability that `k` events occur at the same time with the specified lambda value.
3. Plots the PMF from 0 to `k` occurrences using Matplotlib.

## Example Usage

Here's an example of how to use the function:

```python
poisson_pmf(k=10, lambda_val=5)
```
## Dependencies

The code uses the following Python libraries:
1. Numpy
2. Matplotlib
3. SciPy
