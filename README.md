# Multi-criteria-project
To run the project, please follow the following steps: 

1. Install numpy, pandas (newest version)

2. Replace the data.csv with your data file
Your data file should have the same format as the data_sample.csv

3. Replace the weight.csv with your weight file
Your weight file should have the same format as the weight.csv

4. If you want to run the AHP method, go to AHP.ipynb and run all cells of the notebook

5. If you want to run the VIKOR method, go to VIKOR.ipynb:
+ Find the variable "criteria_importance" and the change value following your criteria importance
For example: if you want to minimize price (criteria 1), maximize benefit (criteria 2)
=> criteria_importance = ['min', 'max']
+ Run all the cells in the notebook 
