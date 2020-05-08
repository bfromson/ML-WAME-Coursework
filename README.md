# ML-WAME-Coursework

The main notebook is “WAME_framework.ipynb”. The datafile with all the landsat data “sat.all.csv” needs to be in the same directory as the notebook and a subdirectory “DataForRuns” needs to be present and have all the csv files for the various experiments.

In the first cell of the notebook the name of the csv file to be processed can be entered. The DataForRuns directory name is specified here as well.

The second cell contains all the imports for the whole workbook. All the modules refernced will need to be installed for the nortebook to work.

The individual blocks are then executed all the way down to the cell after the Store label which saves the results. 

The final cells run the model on the Test data and should only be used when a model has been selected. Over frequent use of the Test dataset will lead to leakage of information from test into the model build and invalidate it.
