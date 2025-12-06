# Simple-Linear-Optimization-Model
Minimum-Cost Production Planning
# Problem:

A company must produce a product using two factories: Factory A and Factory B.
Each factory has a different production cost and a limited capacity.
The company wants to meet customer demand at the minimum total cost.

# Assume:

Factory A cost = 20 € per unit, capacity = 50 units
Factory B cost = 25 € per unit, capacity = 40 units
Customer demand = 60 units in total

# Goal: Decide how many units to produce in each factory to minimize cost while:

Meeting demand.
Not exceeding each factory’s capacity.

# Mathematical model

# Decision variables

F_A = units produced in Factory A
F_B = units produced in Factory B
Both must be >= 0

# Objective:

min 20*F_A + 25*F_B

# Constraints:

Meet demand: F_A + F_B >= 60
capacity of Factory A: F_A <= 50
capacity of Factory B: F_B <= 40
Non-negativity: F_A >= 0, F_B >= 0
