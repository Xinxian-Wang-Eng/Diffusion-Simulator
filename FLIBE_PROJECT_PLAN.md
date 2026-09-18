# SALT URAP FLiBe Microelectrode Multiphysics Modeling

## Project objective

Develop a validated multiphysics modeling framework for electrochemical microelectrodes operating in molten FLiBe.

The framework will begin with mass transport and progressively incorporate:

1. Transient diffusion
2. Microelectrode geometry
3. Electrochemical boundary reactions
4. Cyclic-voltammetry potential control
5. Current calculation
6. Temperature-dependent FLiBe properties
7. Migration and other coupled physics when justified
8. Electrode degradation or delamination as a later-stage module

## Validation strategy

The model will be developed in stages:

1. Validate diffusion against analytical solutions.
2. Check conservation, nonnegativity, and numerical convergence.
3. Validate microelectrode transport against established benchmarks.
4. Add electrode kinetics and verify flux-current consistency.
5. Simulate cyclic voltammetry.
6. Parameterize and validate the model for molten FLiBe.

## Previous project foundation

This branch is based on the earlier two-dimensional free-diffusion project.
Its modular structure, transport solvers, validation tests, and visualization
methods will be reused where appropriate.

## Outline
Step 1: Revise existing code to simulate diffusion based on cylindrical and spherical coordinates
Step 2: Look for proper validation methods and data-fitting algorithms that can help validate simulation results
