## Optimization Model Building on Gurobi

This is a basic network model considering 2 surplus cities (Seattle and San Francisco) and 
3 deficit cities (Boise, Salt Lake City, and Los Angeles)

**Decision Variable** is the number of units being transferred from surplus to deficit stores

**Constraints** are 
  - The total supply out of the stores should not exceed what they are in surplus of 
  - The deficit stores should not receive more than what they are in deficit of

**Objective Function** is to maximize profit which is the difference between the revenue 
and the shipping cost associated with making the transfer from surplus to deficit stores

**Process:** 
I have created 3 cost dictionaries for 3 different use-cases to demonstrate the difference 
in the decision variables as the model tries to maximise the profit
