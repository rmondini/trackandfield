# trackandfield

We analyze the World Athletics (formerly known as International Association of Athletics Federations - IAAF) 100-meter and 200-meter all-time men and women lists. The code is written in Python 3 and contained in a Jupyter notebook.  

The code does the following:  

- Scrapes data from the World Athletics website  
- Builds Pandas DataFrames containing all the relevant information  
- Performs data cleaning and pre-processing
- Performs several exploratory analyses on the 100m lists and produces plots to visualize the findings  
- Uses Machine Learning tools to build two different models (linear regression vs neural network) that predict an athlete's 200m Personal Best (PB) based on their 100m PB, age at 100m PB, gender, and nationality 
- Tests and compares the two models to determine which is the most accurate one (using R2 scores and residual plots).
  
See the jupyter notebook for the code, more details, and references.
