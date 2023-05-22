# GraduateCoursework

In the fall of 2021, I started a part-time graduate degree in mathematical and computational finance at the University of Montreal. I have decided to publish some of my more interesting coursework here.

## IFT6512 (Fall 2021 semester)
Applied stochastic optimization problems

Files:
- `L-shaped_algorithm_JULIA.ipynb` [Julia] -> implements the multicut L-shaped algorithm to solve a two-stage stochastic optimization problem
- `Retrospective_Approximation_JULIA.ipynb` [Julia] -> implements Monte Carlo approximation using the "retrospective approximation" variant of the sample average approximation approach
- `Importance_Sampling_PYTHON.ipynb` [Python] -> implements a Monte Carlo optimization on real electricity production/usage data, comparing "naive" sampling to an approach proposed by Dantzig and Glynn in 1990, "importance" sampling

## IFT6521 (Winter 2023 semester)
Dynamic programming problems  

Files:
- `01-beer_inventory_optimizer.ipynb` [Python] -> optimizes the number of cases of beer a convenience store needs to order to maximize its profits, conditional to previous days' demand in the same week
- `02-asset_purchase_optimizer.ipynb` [Python] -> attempts to pay less than the current market price for a financial asset while still purchasing said asset within a set timeframe
- `03-masters_degree_courseload_optimizer.ipynb` [Python] -> optimizes course selection and the allocation of one's time and efforts to each course, with the goal of minimizing the time required to complete the university's master's degree in mathematical and computational finance
- `03-masters_degree_courseload_optimizer-report.pdf` [Markdown - French] -> detailed report explaining the latter problem, the modeling approach and the results obtained
