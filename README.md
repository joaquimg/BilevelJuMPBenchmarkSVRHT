# BilevelJuMPBenchmarkSVRHT

Companion to the technical report:

Comparing BilevelJuMP.jl Formulations: Support Vector Regression Hyperparameter Tuning

## Running experiments

All solvers are included and assumed installed.

To run a subset, comment the other solvers.

Steps:

1. Clone this repository.
2. Change directory to this folder.
3. Run in command line:

```julia
include("runbench.jl")
```

## Generating tables:

Steps:

1. Change directory to this folder.
2. Run in command line:

```julia
include("table/table.jl")
```