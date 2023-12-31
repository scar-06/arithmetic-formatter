# Arithmetic Formatter

This is the boilerplate for an arithmetic formatter. 

Students in primary school often arrange arithmetic problems vertically to make them easier to solve. For example, "235 + 52" becomes:
```
  235 
+  52 
-----
```

I created a function that receives a list of strings that are arithmetic problems and returns the problems arranged vertically and side-by-side. The function optionally takes a second argument. When the second argument is set to True, the answers are displayed.

### For example
Function Call:
```py
arithmetic_arranger(["32 + 698", "3801 - 2", "45 + 43", "123 + 49"])
```

Output:
```

   32      3801      45      123
+ 698    -    2    + 43    +  49
-----    ------    ----    -----
```

Function Call:
```py
arithmetic_arranger(["32 + 8", "1 - 3801", "9999 + 9999", "523 - 49"], True)
```

Output:
```
  32         1      9999      523 
+  8    - 3801    + 9999    -  49 
----    ------    ------    ----- 
  40     -3800     19998      474
```
