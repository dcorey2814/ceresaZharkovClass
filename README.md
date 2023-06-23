# ceresaZharkovClass
This repository contains code used in the paper "The Ceresa class and tropical curves of hyperelliptic type", arXiv: 2204.06316 by Daniel Corey and Wanlin Li. 

This code works with OSCAR version 0.12.1. Note: it may be essential to use this version of OSCAR. To ensure this, do the following. First, run `julia --project=.` in the terminal from the root of this project. Next, open julia and run the following:

```
julia> using Pkg
julia> Pkg.instantiate()
```

The jupyter notebook `L3.ipynb` contains the details of the calculation asserted in the proof of Proposition 5.9. 
