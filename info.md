# Monte Carlo Sims.

- Most quantum many-body systems in 1D and most bosonic systems can be solved using monte-carlo methods.
- But due to the sign problem(?) the same can't be said for systems in 3D.
- One does [QMC](#quantum-monte-carlo-(qmc)) as there is no other method equipped to treat the quantum many-body system apart from direct simulation where electrons and ions are directly replaced as particles rather than the fluid.
- Most QMC methods are based on random walks(mathematically known as [Markov Process](#markov-process))

## Quantum Monte Carlo (QMC)
- Method used to simulate quantum systems.
> Quantum Systems : Systems that follow quantum mechanical behavior.
- Like in traditional monte-carlo we use random sampling to obtain the statistical average of physical observables(measurable quantities).
- Basic principle is to evaluate the expectation values of the system using Monte Carlo methods.

## Markov Process
- Random process having the property that , "probability of transition from a given state to any future states depends only on the present state."
- It is a stochastic process.
> Stochastic Process : also called a random process. Describes the evolution of a system over time in a probabilistic manner.

$P[X(t_n) = x_n[X(t_{n-1}) = x_{n-1}]]$
for all $X(t_0),X(t_1)....X(t_n)$

where $X(t)$ is the observation at time t.
### Doubts : 
- Quantum Many Body system.

