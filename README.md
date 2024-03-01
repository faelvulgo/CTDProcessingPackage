# CTDProcessingPackage
Python package for pre-processing CTD data

# How to install it
```pip install CTDProcessingPackage```

# How to use it
```Python
import ctdmodule as ctd
```
# Package functions
- plot: plot a simple temperature profile
- plot_perfil_termosal: plot a temperature and salinity profile together
- diagramats: plot a T-S diagram with density isolines
- convert: convert the decimal and thousands separator
- downcast: overwrite the data maintaining only the CTD dowcast data
- remove_outliers: remove the data outliers using the 3-sigma method
- above_sea_level: remove the data collected above the sea level
- pressure_loops: remove the pressure loops from the data
- bin_average: bin averaging 

# Quick Start
Check the quickstart.ipynb notebook for a quick start guide on the package functions

Rafael S. Bittencourt
