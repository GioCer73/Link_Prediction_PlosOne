# Link_Prediction_PlosOne
This repository contains the main Stata code for the paper submitted to PlosOne titled "Link prediction and feature relevance in knowledge networks: a machine learning approach" by A. Zinilli and G. Cerulli, 2022

INSTRUCTIONS TO REPRODUCE THE RESULTS OF THE PAPER

1. The main Stata DO-file to run is "Main_code_to_make_public.do".

2. This DO-file uses the Stata ADO-file "c_ml_stata.ado".
   This file must be located into the Stata subdirectory "ado\plus\c". 
   For example, in my Mac, this is the name of the directory:
   "/Users/cerulli/Library/Application Support/Stata/ado/plus/c"
   
3. The ADO-file "c_ml_stata.ado" calls Python scripts performing the different classifiers (learners) 
   estimated in the paper. These scripts have extension ".py" and are all contained into the 
   "Python_learners" folder. You must cut and paste these python scripts into the Stata 
    sub-directory "ado/plus/py". For example, in my Mac, this is the name of the directory:
   "/Users/cerulli/Library/Application Support/Stata/ado/plus/py"
   
IMPORTANT: if you do not know where your Stata plus directory is located, you must type the command:
. sysdir
and you will know the correct path. 
