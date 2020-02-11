# CCP Coronavirus Prediction
This project aims to predict the numbers that CCP are publishing in each day regarding the amount of Coronavirus cases and deaths.

# Requirements
1. A machine with Python 3 installed.
2. The following packages are needed to be installed for this project to run:
    - numpy
    - matplotlib
    - scikit-learn
    - BeautifulSoup

# How to use
1. Install the required packages (as mentioned above).
2. Run the main.py file using Python 3.

# How does it work?
The main.py file uses the DataGrabber class (source included) to fetch the required data from https://www.worldometers.info.  
The main.py file then trains 2 models using the fetched data and scikit-learn's LinearRegression - the cases per day model  
and then the deaths per day model.  
Afterwards, the file displays statistics about the model (the RMSE and R2 values) and displays a graph for each model that shows how well it scores
(*spoiler alert*: it scores pretty well).
