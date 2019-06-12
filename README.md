# Overview
The project is an SMU capstone project to understand Flowserves customer puchase behavior and idetnifying customer churn.

# Required Applications
Python\
Git\
IDE (VSCode, Sublime, Spyder, etc...)

# Set-up
It is recommended to use the Anaconda distribution of python where you can create different environments.

The environment can be created by:
```
conda env create -f env_custbb.yml
```

To activate the environment use the following:\
windows -> ```activate custbb```\
linux -> ```conda activate custbb```

# Data
The data in contained in the ```data``` directory.  The total amount if ~2.7GB from January 2014 to May 2019.  The data is split by year and is ~500MB per file.

The data is anonimyzed to protect out customers.  The files you should be working with are files that start with 'data_anon_...'.

When loading data into a pandas DataFrame ensure encode the data with 'latin-1'.

# Code
Place all your code in the 'src' directory.