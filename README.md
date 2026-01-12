# Geothermal Potential Uncertainty and Sensitivity Analysis

# 1.Description

This repository contains the Python code used in the study on geothermal potential assessment based on uncertainty quantification and global sensitivity analysis.

The code implements:
- Monte Carlo simulation for uncertainty propagation
- Sobol global sensitivity analysis
- Spatial variance estimation of geothermal potential indicators

The workflow supports the generation of uncertainty maps and sensitivity indices used to
interpret the dominant controlling factors of geothermal potential.

The scripts were developed and tested in a Python 3.9.23 environment and were used to generate
the results presented in the associated manuscript.


# 2.Installation

# 2.1 Environment
- Python 3.9.23
- NumPy
- Pandas
- Rasterio
- SciPy
- SALib
- Matplotlib

# 2.2 Dependency Installation
Install required packages using:
pip install numpy 
pip install pandas 
pip install rasterio 
pip install scipy 
pip install SALib 
pip install matplotlib

# 3.Execution

3.1 Prepare the input data and place it in the appropriate directory.
   - Excel file containing coordinates and the corresponding parameter statistics

3.2 Open the code file: 
   -CODE-public available.ipynb

3.3 Run all cells sequentially from top to bottom.

3.4 Output files will be automatically saved to the specified output directory, including:
   - Monte Carlo simulation results
   - Sobol sensitivity indices
   - Variance summary tables

#4. Reproducibility

All stochastic processes are controlled using fixed random seeds.
The results reported in the manuscript can be reproduced by executing the "CODE-public available.ipynb" with the provided data and environment configuration.
While Some input data may not be publicly available due to data policy restrictions.
