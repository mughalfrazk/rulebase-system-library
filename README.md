# How it works

Run the command:
```
pip install RulebaseProductionSystem
```

Import `planner` method from the library in yout python project
```
from RulebaseProductionSystem import planner
```
Use the planner method from library
```
plan = planner.planner(initial_state=[], final_state=[], positions={}, constraints=[], facts=[], iteration_limit=1000)
``` 
