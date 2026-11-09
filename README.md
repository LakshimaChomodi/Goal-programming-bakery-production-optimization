# Goal-programming-bakery-production-optimization
MATLAB implementation of a goal programming model for bakery production planning, balancing profit, cost, and overtime priorities in a real-world case study.
# Application of Goal Programming Model: Bakery Production Case Study

This project applies goal programming in MATLAB to a bakery production planning problem. The model considers weekly production of bread and buns while balancing profit, cost, and overtime priorities.

## Project objectives

The model aims to:

1. Meet the target for weekly profit.
2. Keep total weekly costs within the specified limit.
3. Avoid overtime for packing.
4. Avoid overtime for baking.

## Method

The weekly quantities of bread and buns are the decision variables. Goal programming represents each target with deviation variables and uses MATLAB's `linprog` function to find a production plan based on the stated priorities.

## Run the MATLAB code

1. Download or clone this repository.
2. Open `Goal Programming.m` in MATLAB.
3. Run the script.

The project report and MATLAB script are included in this repository.
