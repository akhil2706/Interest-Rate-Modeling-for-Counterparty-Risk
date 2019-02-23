# Interest Rate Modeling for Counterparty Risk

Simulated interest rate curves using the Heath Jarrow Merton framework to compute the CVA charge for a vanilla interest rate swap. Developed a 3 factor interest rate model. The volatility for factors of the model was computed by performing PCA analysis on the Bank of England 10r yield curve and the drift was computed from the volatility surfaces. 

## Getting Started 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites 

This project requires a Python2.7 environment with the following dependencies: 
1) Pandas 
2) Numpy
3) SciPy
4) Matplotlib
5) Sklearn
 

### Installation

The code for the strategy has been implemented in the .ipynb file included in the repository and can be replicated with the consent of the contributors.

## Testing 

The IPython notebook containts the code and the descriptive comments which debrief about the functionality of each function used. To begin implementation, run the 'cva()' function. This function requires the users to pass input paramters defined the implemented function. The yield curve data from which implied volatility was found out is present in the 'Data.csv' file. 

## Contributors 

Akhil Sethia

