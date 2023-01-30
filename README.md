# Installation of PyMC with ProPlot

1. Create virtual environment using conda and activate the env.
```
conda create -n pymc-env python=3.10
conda activate pymc-env
```

2. Update conda
```
conda update -n base -c conda-forge conda
```

3. Install proplot from github repository.
```
pip install git+https://github.com/proplot-dev/proplot.git
```

4. Install `pymc>=4` using conda.
```
conda install -c conda-forge "pymc>=4"
```

5. Install additional libraries to run test script.

```
conda install -c conda-forge ipykernel pandas scipy arviz python-graphviz
```

6. Run example notebook file (`pymc-test.ipynb`) and make sure it works properly.
