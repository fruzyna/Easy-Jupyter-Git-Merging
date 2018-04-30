# Easy-Jupyter-Git-Merging
Saves Jupyter notebooks as python files to allow easier merge conflict handling. 

## Saving Notebooks Automatically to .py
Python notebooks don't work very well with git. Please refer [here](https://stackoverflow.com/questions/18734739/using-ipython-notebooks-under-version-control/25765194#25765194) to setup Jupyter to automatically save a .py version. In summary copy the jupyter_notebook_config.py file to your Jupyter config directory located by running: jupyter --config-dir

Alternatively, you could save it manually via: File > Download as > Python (.py)

## Converting back to a Notebook
Simply run the included convert-to-notebook.py to convert all other .py files to .ipynb notebooks. This must be run with the same version of python that is used in Jupyter to ensure that the proper libraries are installed.
