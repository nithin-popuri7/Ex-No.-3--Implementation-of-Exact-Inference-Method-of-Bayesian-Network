# Ex No. 3- Implementation of Exact Inference Method of Bayesian Network

## Aim:
To implement the inference Burglary P(B| j,⥗m) in alarm problem by using Variable Elimination method in Python.

## Algorithm:
### Step 1:
Define the Bayesian Network structure for alarm problem with 5 random 
             variables, Burglary,Earthquake,John Call,Mary Call and Alarm.<br>
### Step 2: 
Define the Conditional Probability Distributions (CPDs) for each variable 
            using the TabularCPD class from the pgmpy library.<br>
### Step 3: 
Add the CPDs to the network.<br>
### Step 4: 
Initialize the inference engine using the VariableElimination class from 
             the pgmpy library.<br>
### Step 5: 
Define the evidence (observed variables) and query variables.<br>
### Step 6:
Perform exact inference using the defined evidence and query variables.<br>
### Step 7: 
Print the results.<br>

## Program :
```
Name:P.Siva Naga Nithin
Reg.No:212221240037
```
```
from pgmpy.models import BayesianNetwork
from pgmpy.factors.discrete import TabularCPD
from pgmpy.infrence import VariableElimination

network = BayesianNetwork([
    ('Burglary','Alaram'),
    ('Earthquake','Alaram'),
    
    ('Alaram','MarryCall'),
])
```



## Output :

## Result :  


