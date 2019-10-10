# evolution-strategies

Here I implement CMA-ES and NES algorithms.  

Both 1d and 2d visualizations supported, although freezes frequently and clears all the necessary output (matplotlib+ipython related issue I guess).

Peculiarities:  
NES turned out to be quite numerically unstable on multimodal functions.  
Had a look on PyBrain implementation of this algorithm (which is slightly more optimized) and found out the same problems,
so I guess this is inherent for the NES algorithm (the base one, probably other variants like XNES/SNES behave differently).

CMA-ES works as expected.
