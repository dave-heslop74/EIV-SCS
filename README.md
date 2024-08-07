#### Python code demonstrating Bayesian errors-in-variables regression estimation of specific climate sensitivity

The provided Jupyter notebooks recreate the casy study example given in *Bayesian errors-in-variables estimation of specific climate sensitivity*
by D. Heslop (david.heslop@anu.edu.au), E.J. Rohling, G. L. Foster, & J. Yu, submitted.

#### Required packages
- ```Numpy```: https://numpy.org/
- ```Scipy```: https://scipy.org/
- ```Matplotlib```: https://matplotlib.org/
- ```Emcee```: https://emcee.readthedocs.io/en/stable/#
- ```Pathos```: https://pypi.org/project/pathos/
- ```Pandas```: https://pandas.pydata.org/

#### Data files
- ```500kyrCO2.csv```: CenCO2PIP ln(CO2) data (500kyr windows)
- ```500kyrTemp.csv```: CenCO2PIP ΔGMST data (500kyr windows)

#### Jupyter notebooks
- ```2024PA004880 - MLE example.ipnb```: Demonstration of maximum likelihood estimation (recreates Figure 2).
- ```2024PA004880 - BIV example.ipnb```: Demonstration of Bayesian EIV estimation (recreates Figure 3).
- ```2024PA004880 - Eocene example.ipynb```: Eocene case study (recreates Figure 4).
