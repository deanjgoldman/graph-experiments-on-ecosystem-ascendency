# Simulating Ascendency Statistics from the South Florida Ecosystems Dataset

This project is an exploration of the South Florida Ecosystems Dataset, with the specific goal of investigating the relationship between energy exchange among ecosystem taxa (different species) and indices of ecological organization such as: ascendency, capacity, and overhead. 

[Paper](https://github.com/deanjgoldman/graph-experiments-on-ecosystem-ascendency/blob/master/Simulating%20Ascendency%20Statistics%20from%20the%20South%20Florida%20Ecosystems%20Dataset.pdf)

[Soure Code](https://github.com/deanjgoldman/graph-experiments-on-ecosystem-ascendency/blob/master/Graph%20Experiments%20on%20Ecosystem%20Ascendency.ipynb)

## Requirements (Ubuntu 18.04):

```
sudo apt-get install libpython3.10-dev
sudo apt-get install graphviz-dev

python3.10 -m virtualenv sffw-env
source sffw-env/bin/activate
python -m pip install -r requirements.txt
```

## Notes
This repo overrides the original networkx library to support parsing these custom .paj files.  
  
The paj files in this repo were sourced from: http://networkdata.ics.uci.edu/netdata/html/floridaFoodWebs.html, but have been modified to fix typos and unify certain species names. 

## To run:
Load jupyter-notebook, read in-line documentation, execute cells.

# References
Ulanowicz, Robert & Heymans, Johanna & Bondavalli, C. (2002). Network analysis of the South Florida Everglades and graminoid marshes and comparison with nearby cypress ecosystems. Ecological Modeling 149 (2002) 5-23.

Ulanowicz, R.E. (1986). Theoretical ecology: Ecosystem ascendency. pp. 481-483. In: 1987 Yearbook of Science and Technology McGraw-Hill, NY. https://people.clas.ufl.edu/ulan/files/McGrwHll.pdf

Aric A. Hagberg, Daniel A. Schult and Pieter J. Swart, “Exploring network structure, dynamics, and function using NetworkX”, in Proceedings of the 7th Python in Science Conference (SciPy2008), Gäel Varoquaux, Travis Vaught, and Jarrod Millman (Eds), (Pasadena, CA USA), pp. 11–15, Aug 2008

Borrett & Lau (2014) enaR: An r package for Ecosystem Network Analysis. Methods in Ecology and Evolution 5: 1206-1213.
