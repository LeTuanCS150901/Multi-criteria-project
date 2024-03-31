# Multi-criteria-project
To run the project, please follow the following steps:

1.Install numpy, pandas (newest version)

2. Replace the data_sample.csv with your data file
Your data file should have the same format as the data_sample.csv

3. Replace the weight_sample_VIKOR.csv with your weight file
Your weight file should have the same format as the weight_sample_VIKOR.csv

4. If you want to run the AHP method, go to AHP.ipynb and run all cells of the notebook

5. If you want to run the VIKOR method, go to VIKOR.ipynb:
+ Find the variable "criteria_importance" and the change value following your criteria importance
For example: if you want to minimize price (critera 1), maximize benefit (critera 2)
=> criteria_importance = ['min', 'max]
+ Run all the cell in the notebook 
