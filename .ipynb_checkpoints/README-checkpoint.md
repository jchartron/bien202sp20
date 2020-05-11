# Class resources for BIEN 202

You can create an environment for running BasicPython.ipynb with the following conda commands:

```
conda create -n yournamehere jupyterlab numpy scipy sympy matplotlib
conda activate yournamehere
conda install -c alubbock pysb
```

Clone this repository and fire up jupyter lab:

```
git clone https://github.com/jchartron/bien202sp20.git
cd bien202sp20
jupyter lab
```