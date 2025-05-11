# Python String Operations Compare
This project is for the UMD Course 605 - Computing Systems for Machine Learning.

In this proejct I compare the Python's default string operations to the more memory and time efficient PyArrow alternatives.

## How to create the conda envirment and install dependencies.
1. Use the following command in your terminal/Anaconda Prompt (for Windows) to build the conda environment.
   conda env create -f environment.yml

   or createa a new environment using
   conda create -n <environment-name> python=3.7
3. Activate the environment
   source activate <environment-name>
   the name of the already created environment in .yml file is `base`.
4. Install requirements by using the following command:
   pip install -r requirements.txt

Then open the string-ops-compare.ipynb and run the notebook. Make sure that the right kernel (environment) is selected in the notebook. Run the code sequentially to reproduce the results.
   
