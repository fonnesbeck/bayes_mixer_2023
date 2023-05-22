# Bayesian Best Practices

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/distribution/#download-section) (Python 3.11 version) or [Mambaforge](https://github.com/conda-forge/miniforge#mambaforge) (preferred) setup and installed on your system.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/bayesian_workflow.git
    
otherwise you can [download a zip file](https://github.com/fonnesbeck/bayesian_workflow/archive/master.zip) of its contents, and unzip it on your computer.

In either case, you should now have a directory called `bayesian_workflow` in your current working directory.

    cd bayesian_workflow

The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create
    
from the main tutorial directory, it will create the environment (called `bayes`) for you and install all of the packages listed. This environment can be enabled using:

    conda activate bayes
    
Then, I recommend using JupyterLab (or your favorite Jupyter-supporting editor) to access the materials:

    jupyter lab