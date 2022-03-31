# structural-template-lattice

This directory provides the necessary files to navigate the pattern concept lattice for the case study of code sophistication.
The lattice structure is contained in template-lattice.json
The navigation interface is provided in the Jupyter notebook ExplSearch-ICSR22.ipynb

You can run the notebook locally if you have a local notebook environement.
It was written with Python 3.8 and uses the four modules json, networkx, ipywidgets and IPython.

Otherwise, it can be run online using Google Colab for instance.
In Google Colab, simply import the notebook and loads the json file in the "content" directory (it can take a few minutes to load this file).

Once every cells are executed (Run > Run All Cells), the last cell will display an interface to navigate the templates loaded from the json file.