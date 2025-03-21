# contspace-cpmodel-agriculture

This repository provides simulation codes for an evolution equation discussed in the following paper.  
I would appreciate your citing the following paper when you publish your results using this code.

```
@article{ohtake2025continuous,
  title={Continuous space core-periphery model with transport costs in differentiated agriculture},
  author={Ohtake, Kensuke},
  journal={Portuguese Economic Journal},
  pages={1--34},
  year={2025},
  publisher={Springer}
}
```

# overview
Language: Julia ver 1.10.2  
Packages:  
CSV ver. 0.10.13  
DataFrames ver. 1.6.1  
Distributions ver. 0.25.107  
Format ver. 1.3.7  
IJulia ver. 1.24.2  
Plots ver. 1.40.2

How to use:  
In the second cell, specify the values of $\tau^M>0$ as the list used in the outer loop.  
Then, specify parameters $\eta>1$, $\sigma>1$, $\tau^A>0$ in the list used in the inner loop.  
For a set of parameters, five simulations are performed for randomly generated initial values.

