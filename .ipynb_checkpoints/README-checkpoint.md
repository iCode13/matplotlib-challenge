# Matplotlib Challenge: Pymaceuticals
An analysis of the performance of Pymaceuticals' anti-cancer drug, Capomulin, as compared to the other treatment regimens. 

## General Info:
Pymaceuticals Inc. is a pharmaceutical company that specializes in anti-cancer pharmaceuticals. It has recently begun screening for potential treatments for a common form of skin cancer, called squamous cell carcinoma (SCC). In their recent animal study, 249 mice with SCC tumor growth were treated through a variety of drug regimens, and tumor development was observed and measured over a timespan of 45 days. This study aims to analyze data from the study, and compare the performance of the drug, Capomulin, versus the other treatment regimens.  

## Data Set:
Two datasets of the laboratory study analyzed is available as a Comma Separated Values (CSV) files in the Data folder within the project directory (https://github.com/iCode13/matplotlib-challenge/tree/master/data). These datasets provided two kinds of information:
    1) Information on the subjects, the mice -- including their IDs, sex, age, and weight;  
    2) Data gathered during the laboratory study -- including the drug regimen they are on, tumor volumes measured over progressive timepoints, and the number of metastatic sites found.
    
## Technologies:
The languages, libraries and other tools used in this project are as below, and with their versions:

    Python - version 3.7.8
    
    Pandas - version 20.1.1
    
    Matplotlib - version 3.3.0
    
    Scipy - version 1.5.1
    
    Jupyter Notebook

## Actions and Tasks:
- Data Cleaning and Exploration
- Data Analysis and Visualization
- Writing Analysis and Conclusions
    
## Analysis & Conclusions:
Analysis of the data revealed the following:
    - A total of 10 drug regimens were part of the study, including a placebo. Out of the 10, detailed analysis was performed for 4 drugs -- Capomunil, Capomulin, Ramicane, Infubinol, and 
      Ceftamin that showed the best results.
    - The laboratory mice cohort consisted of 248 mice, including one that was erroneously measured more than once at certain timepoints. The cohort had a nearly equal male to female ratio. 
      About a 100 mice went through the above mentioned 4 drug regimens.
    - Mice that participated in the Ramicane and Capomulin drug regimens showed markedly lower mean total tumor volumes (along with low variance) when compared to those in other drug 
      regimens.
    - The number of mice subjected to each drug regimen hovered around 24-25.
    - Quartile calculations on final tumor volumes revealed no outliers in case of all 4 drug regimens. Capomulin and Ramicane showed marked less quartile values than Infubinol and Ceftamin, 
      as well as lower variance in final tumor volumes. However, box and whisker plot reveals a single outlier for Infubinol.
    - Line plot shows a gradual decrease in tumor volume over time for mouse ID = x401. The trend was similar for majority of the mice.
    - The scatter plot and regression model revealed a high correlation between mice weight and final tumor volume (correlation coefficient = 0.842).
      
## Contact
Created by [@iCode13](https://github.com/iCode13) - please feel free to contact me!

![Laboratory.jpg](/home/jupyter/matplotlib-challenge/Data/Laboratory.jpg)