# Optimal_classification_trees

According to the research paper published by Professor Dimitris Bertsimas and Jack Dunn in 2017, the optimal classification trees algorithm can directly create the entire tree structure to achieve global optimality.

The research paper link:
http://www.mit.edu/~dbertsim/papers/Machine%20Learning%20under%20a%20Modern%20Optimization%20Lens/Optimal_classification_trees_MachineLearning.pdf

Motivated by the rapid development of optimization theory and hardware improvements, we can present this algorithm via mixed-integer optimization now.

## Setup 
Before the implementation, we need to finish the setup of Python interface with Gurobi (in order to import gurobipy).
https://www.gurobi.com/resource/modeling-with-the-gurobi-python-interface/

```shell
from gurobipy import *
from io import StringIO
import requests
m = Model('mip1')
```

After importing gurobipy and initializing a model, we can see this below the shell.
```shell
Academic license - for non-commercial use only
```
