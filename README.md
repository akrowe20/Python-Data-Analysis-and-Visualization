# Python-Data-Analysis-and-Visualization

The following jupyter notebooks have been adapted from the Carpentries material [Data Analysis and Visualization in Python for Ecologists](https://datacarpentry.github.io/python-ecology-lesson/) for use in teaching Python.

## Python Installation

These Python notebooks use several packages which need to be installed in addition to Python itself. There are many ways to install all these requirements depending on your preference with using a Graphic User interfaces (GUI) or a Command-line Interface (CLI).

GUI Option – Using [Anaconda](https://www.anaconda.com/)

Anaconda is a data science platform which comes with all but one of the required packages needed for the Python workshop. Please [download](https://www.anaconda.com/download) (you can skip the registration) and install Anaconda, accepting the default options during installation. To install the missing package please do the following: 
1.	Open the Anaconda Navigator and click the "Environments" button on the left.
2.	Change the “Installed” dropdown to “Not installed”,  then enter *plotnine* in the search packages field
3.	From the list of packages, click the empty box next to *plotnine*, then click Apply

Once complete, go back to the main tab and open Jupyter Lab and then navigate to where you've cloned this repository.

CLI Option – Using [Miniconda](https://docs.anaconda.com/miniconda/)

Miniconda is a lightweight version of Anaconda. 
It can be installed completely from the CLI with [installation instructions for all operating systems](https://docs.anaconda.com/miniconda/install/#quick-command-line-install). 
With Miniconda installed, you should see '(base)' at the start a new line in your CLI (you may need to close and reopen your CLI). If you do not see '(base)', from the CLI execute 
```conda activate base```
We’ll also need to install all the packages required for this workshop. The quickest way to install these packages is by running the following *conda* commands from the CLI:

1.	conda install -y numpy pandas matplotlib jupyter
2.	conda install -c conda-forge plotnine

One complete, from the CLI, execute ```jupyter lab```

It should be noted that Anaconda and Miniconda are free for research purposes, but should you require a solution without limitations on use, please try the Miniconda equivalent [Conda Forge](https://conda-forge.org/). The above conda commands for installing the required packages are the same.

