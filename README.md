# Recession-Prediction

How to run the code

Running Python Notebook 1 (recession-predictor.ipynb)
This file contains the datasets and the majority of the project

Navigate to this shared google colab file
As you run each cell, you may be prompted to upload a file
The 2nd cell prompts you to upload a kaggle.json file so we can access the us-recession-and-financial-indicators data source via API

To obtain a kaggle.json file if you do not have one already:
1. Go to your Kaggle account settings.
2. Scroll down to the API section and click Create New API Token. This will download a kaggle.json file to your computer.

Once the Kaggle datasource has been imported, the 4th cell will prompt you for a file. This is the label dataset. 
Please upload the USREC.csv file 

Later in the notebook, there is a section called "A new approach"
This section will prompt you to upload 2 files
The first file is the 10 year treasury yield. Please upload the file called called DGS10.csv
The second file in the following cell is the 2 year treasury yield. Please upload the file called DGS2.csv


Running Python Notebook 2 (rogueSpear.ipynb)
This file takes the output of our cleaned datasets from recession-predictor.ipynb and runs them through the models again and focuses on hyperparameter tuning

Navigate to this shared google colab file
The first cell will prompt you to upload 2 files:
1. phase1Model.csv - our original cleaned dataset
2. m76r.csv - our enhanced dataset that extends further back in time and has new features
