# Using-Lagrangian-Relaxation-on-the-budget-constraint
This is an inventory control model with budget constraint which the objective function minimizes total costs and the decision variables are number of pieces per order for each product (Q_i). This algorithm first calculates Q_i via Wilson formula then calculates the total cost which imposed by this amount of ordering. if This cost exceeds the budget, it will calculate the optimal Q_i by forming its Lagrange function.