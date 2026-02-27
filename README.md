# MSDS-492—Final Project 
Checkpoint C files
### Code overview for Final Project - MSDS 492- David Van Dyke

The markdown section in the *.ipynb files explains the function of each of the code block.  This README file contains a quick background on each of the sections.  If you have any trouble running the code, please reach out to let me know.  Thanks Dave Van Dyke
There are 3 main sections in the code for the different parts of the study.  There are various subsections described below

1.	Section #1- Data gathering and preparation
•	Downloads the last ~15 years of data yfinance data for the assets into an Excel Worksheet. Marathon Petroleum Corporation (MPC), Phillips 66 (PSX), and Valero Energy Corporation (VLO), the S&P 500 Index (^GSPC), WTI Crude Oil futures (CL=F), Gold futures (GC=F), CBOE Volatility Index (^VIX)
•	This is then read into a pandas data frame
•	Engineered features are added to the data frame
•	The data frame is organized into a machine learning data set
•	Additional engineered features are calculated on the machine learning data set.
•	EDA code blocks are done for the data preparation
•	A refining stock report is done to confirm the stylized facts for financial markets.

2.	Section #2.  Machine learning testing on the base ML dataset
•	Baseline logistic regression model.
•	Testing of the modification to the logistic regression model setup
•	Testing of the advanced non-linear machine learning models

3.	Section #3- Modifications to the dataset for GARCH and OPEC news features
•	Preparation of the new features
•	Integration of the features into the dataset
•	Testing on the logistic regression models
•	EDA checks to confirm feature impacts
•	Testing of all features on the logistic regression and CNN model

4.	This Github repository has folders for the code results files
•	Baseline Logistic Regression model
•	Modified Logistic regression setup
•	Advanced model results
•	Results with the GARCH and OPEC news features
•	Various EDA results
•	OPEC News sources
