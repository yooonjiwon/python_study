# [python] ICD mapping

This code is from [this question's answer](https://stackoverflow.com/questions/60348489/how-to-order-strings-with-numbers-and-letters-in-order-to-categorize-in-python)

```{python}
from bisect import bisect_left

ranges = ["C00","D50","E00","F00","G00","H00","H60","I00",
          "J00","K00","L00","M00","N00","O00","P00","Q00","R00",
          "S00","V00","Z00"]

def icdGroup(code): 
    return bisect_left(ranges,code)
```
