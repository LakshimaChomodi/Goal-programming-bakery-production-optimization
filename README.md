# Goal-programming-bakery-production-optimization
MATLAB implementation of a goal programming model for bakery production planning, balancing profit, cost, and overtime priorities in a real-world case study.
# Bakery Production Planning with Goal Programming

A MATLAB based operations research project that applies goal programming to a weekly production planning case study for Food Art (Pvt) Ltd, a bakery products company.

## Project Overview

The model determines weekly production quantities for bread and buns while considering several management goals. Since these goals may compete with one another, the model represents them using deviation variables and solves the resulting linear programming formulation with MATLAB's `linprog` function.

## Goals Considered

- Achieve the target weekly profit.
- Keep total weekly production costs within the specified limit.
- Minimize packing overtime.
- Minimize baking overtime.

## Model Components

- **Decision variables:** Weekly quantities of bread and buns.
- **Goal constraints:** Profit, production cost, packing hours, and baking hours.
- **Solution method:** Goal programming formulated as a linear programming problem and solved in MATLAB.

## Repository Contents

- `Goal Programming.m` — MATLAB script for the model.
- `123.pdf` — Project report describing the case study, model, and results.

## How to Run

1. Download or clone this repository.
2. Open `Goal Programming.m` in MATLAB.
3. Run the script.

The script uses MATLAB's Optimization Toolbox, which provides the `linprog` function.

## Scope

This is an academic case study. The production recommendations depend on the data, assumptions, and goal structure used in the model.
