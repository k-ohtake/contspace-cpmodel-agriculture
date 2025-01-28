# contspace-cpmodel-agriculture

This repository provides simulation codes for an evolution equation discussed in the following paper.

```
@article{ohtake2022spatial,
  title={Continuous space core-periphery model with transport costs in differentiated agriculture},
  author={Ohtake, Kensuke},
  journal={arXiv preprint arXiv:2206.01040},
  year={2022}
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

