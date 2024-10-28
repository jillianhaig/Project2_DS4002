## Content ##
This repository contains all the necessary files and information to analyze time series hurricane and climate change data. It contains a Data, Output, and Scripts folder where the user can find all of the csv files used to obtain the data, as well as scripts used for transforming and analyzing the final dataset. The repository also contains the README (this file) and the LICENSE markdown files, as well as the final presentation slides for the project. 

## Section 1: Software and platforms used 
The Python programming language was used for all analysis and coding for this project. The packages used in this project that need to be installed include: pandas, matplotlib.pyplot, numpy, seaborn, warnings, VAR, adfuller, rmse, aic, grangercausalitytests, coint_johansen, durbin_watson, and acf. Both Mac and Windows platforms were used in this project.

## Section 2: Map of documentation 
The Project2_DS4002 repository contains the following folders and files:
1. DATA folder: contains the Final Dataset subfolder, where the merged and cleaned dataset (Hurricane_Dataset.csv) can be found. It also contains the Individual Datasets folder, where one can find data for each individual csv file utilized in the study, which were cleaned and merged together to create the final dataset. Finally, the folder contains the Data Appendix pdf document, named DataAppendix.pdf.
2. OUTPUT folder: Contains png files of output from exploratory data analysis (EDA), and data visualizations. This includes any scatterplots, line graphs, relevant code output, and other visualizations the group has created for analysis.
3. SCRIPTS folder: contains three ipynb files which were created by the group to investigate the research question using statistical analysis. The scripts involve data cleaning and creation, EDA, and data analysis.
4. Final project presenation slides (Group 15 Project 2 Presentation.pdf)
5. LICENSE markdown file
6. README markdown file

## Section 3: Instructions for reproducing results 
To replicate the methods and results of this study, one can find all the necessary tools and files from this GitHub repository. After accessing the repository, the user can download all the data from the DATA folder. The 1_Data_Creation_Cleaning.ipynb file must be run first in a coding environment such as Google Colab. This file merges the individual hurricane and climate datasets into one cohesive dataset, and it also cleans the dataset including dropping unnecessary variables. Next, the 2_EDA_Project2.ipynb file can be run to obtain the same results from EDA that the group did. Although not imperative to the analysis for this study, the EDA portion serves as additional context into the research question and dives deeper into the variables used in the dataset. Finally, the 3_Analysis_Project2.ipynb file must be run to obtain results using statistical analysis.

