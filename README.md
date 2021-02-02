# An implementation for diffusion-limited pahse separation in eukatyric chemotaxis

The usage of SSA for chemical reactions opens a paradigm in understanting of chemotaxis processes. In [1] the authors introduce a model for the interaction dynamics of <img src="https://latex.codecogs.com/gif.latex?PI3K " /> ![equation](https://latex.codecogs.com/gif.latex?PI3K)  $PI3K$, $PTEN$, $PIP_{2}$ and $PIP_{3}$ molecular species in the cellular membrane. This reactions occurs on the surface of a sphere and as a simplification (and a tool for computational modelling) we can consider a Voronoi tesselation where is convenient to consider each cell $R_{k}$ with same area as well as same convex hull (except an linear transformation), this way each cell has same number of neighbors and we can neglet the area or form variations as capacity or propensity areas.  

We will extend the Gillespie' SSA from a open-closed-space to a open-closed-grid where each node has its own dynamics and is influenced by its neighbors.

# References

[1] Gamba, A., de Candia, A., Di Talia, S., Coniglio, A., Bussolino, F., & Serini, G. (2005). Diffusion-limited phase separation in eukaryotic chemotaxis. Proceedings Of The National Academy Of Sciences, 102(47), 16927-16932. doi: 10.1073/pnas.0503974102

[2] Gillespie, D. (2007). Stochastic Simulation of Chemical Kinetics. Annual Review Of Physical Chemistry, 58(1), 35-55. doi: 10.1146/annurev.physchem.58.032806.104637

[3] Gillespie, D. (1977). Exact stochastic simulation of coupled chemical reactions. The Journal Of Physical Chemistry, 81(25), 2340-2361. doi: 10.1021/j100540a008
