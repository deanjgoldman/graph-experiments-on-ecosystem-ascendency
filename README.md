# Simulating Ascendency Statistics from the South Florida Ecosystems Dataset

This project is an exploration of the South Florida Ecosystems Dataset, with the specific goal of investigating the relationship between energy exchange among ecosystem taxa (different species) and indices of ecological organization such as: ascendency, capacity, and overhead. 

## Requirements (Ubuntu 18.04):

```
sudo apt-get install libpython3.10-dev
sudo apt-get install graphviz-dev

python3.10 -m virtualenv sffw-env
source sffw-env/bin/activate
python -m pip install -r requirements.txt
```

This repo overrides the original networkx library to support parsing these custom .paj files. The paj files in this repo were sourced from: http://networkdata.ics.uci.edu/netdata/html/floridaFoodWebs.html, but have been modified to fix typos and unify certain species names. 

## To run:
Load jupyter-notebook, read in-line documentation, execute cells!