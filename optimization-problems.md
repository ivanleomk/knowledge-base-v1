# Optimization Problems

We can define an [[optimization]] problem in terms of three requirements

## [[Objective Function]]
This is a function that allows us to evaluate the quality of an optimization choice using an objective function

## [[Decision Variables]]
These represent the quantities that we vary slowly

## [[Constraints]]
The limits on the degree of variation for each individual decision variable. 

Only when we have these three prerequisites can we consider ourselves to have a optimization problem on hand.

# Types Of Optimization Problem

When considering what type of optimization problem we are looking at, we can consider three main categories

1. Discrete vs Continous : Decision variables are either discrete or continous, leading to us having a corresponding discrete or continous optimization problem

```
Sample Discrete Problem: We can buy eggs and brownies. Eggs cost $1 and give us 100 calories while brownies cost $1.50 and give us 200 calories. How many of each should we buy to maximise the number of calories we obtain. (The number of brownies/eggs takes on a discrete integer value. We cannot have for instance 3.14 eggs, we can only have 3 in this case.)

Sample continous problem : We have 20 metres of fence. We want to maximise the area that we fence off and we want to use a rectangular shape. How can we optimize the area we fence off? (Length is a continous variable and can take on any real value)
```

2. Deterministic vs [[Stochastic]] : Sometimes, we are unsure about the value of our decision variables and are only aware of the range that we expect to get them in. 

```
Sample Stochastic problem : We expect to sell 8-12 donuts a day. Each donut costs us $1 and we sell them for $1.10 each. How many donuts should we purchase each day to maximise our profit

Sample Deterministic problem: We can buy eggs and brownies. Eggs cost $1 and give us 100 calories while brownies cost $1.50 and give us 200 calories. How many of each should we buy to maximise the number of calories we obtain
```





