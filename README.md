# Grab Cut

This project implements the grab cut algorithm presented in the paper: [“GrabCut” — Interactive Foreground Extraction using Iterated Graph Cuts
](https://www.microsoft.com/en-us/research/wp-content/uploads/2004/08/siggraph04-grabcut.pdf)

## Data

Images used throughout the project, including in the comparison of the models, can be found in the [samples folder](./samples/)

# Running the Notebook

(Optional, recommended): Create a virtual environment for this notebook. Make sure you have `virtualenv` installed (`pip install virtualenv`). Create the virtual environment by running

```
python3 -m virtualenv grabcut-venv
```

From outside the virtual environment run `python -m ipykernel install --user --name grabcut-venv --display-name "grabcut-py3"`. This allows Jupyter Notebook to use the virtual environment as a kernel specification.

Activate the virtual environment by running: `grabcut-venv\Scripts\activate`

Using `pip` package manager for Python, run the follwoing commands from the root directory of this repository to install all necessary python packages.

```

pip install -r requirements.txt

```

Run the algorithm in [GrabCut.ipynb](./GrabCut.ipynb) in Jupyter Notebook
