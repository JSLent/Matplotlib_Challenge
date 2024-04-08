#Pymaceuticals
#Introduction
Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications, conducted an animal study to screen potential treatments for squamous cell carcinoma (SCC), a common skin cancer. 
The study involved 249 mice with SCC tumors receiving various drug regimens. Over 45 days, tumor development was observed and measured. 
As a senior data analyst, my task was to analyze the data, create essential tables and figures, and provide a high-level summary of the study results.

#Data
Source: The data was obtained from 2 csv files: Mouse_metadata.csv and Study_results.csv
Format: Both files are csv
Processing steps: The data from both csv files were combined using a right join operation in Pandas.  The resulting combined dataset was used for the analysis.

#Analysis
Summary Statistics: Create summary stats for each drug regimen including mean, mediam, variance, standard deviation, and SEM of the tumor volume.  
Create Bar and Pie Charts: Generate 2 bar charts to show the total number of rows for each drug regimen, one using Pandas DataFrame and another using Matplotlib's PyPlot.  Generate 2 pir charts to show the distribution of female vs male mice in the study,
  one using Pandas DataFrame and another using Matplotlib's PyPlot.
Calculate Quartiles, Find Outliers, Create Box Plot: Calculate the final tumor volume for each mouse across four treament regimens.  Calculate quartiles and IQR for each treatment regimen and identify potential outliers.  Generate a box plot to visualize the distribution
  and highlight outliers.
Create a Line Plot and Scatter Plot: Generate a line plot of tumor volume versus time point for a single mouse treated with Capomulin.  Generate a scatter plot of mouse weight vs avg observed tumor volume for the entire Campomulin treatment regimen.  
Calculate Correlation and Regression: Calculate the correlation coefficient and linear regression model between mouse weight and avg observed tumor volume for the entire Capomulin treament regimen.  Plot the linear regression model on top of the scatter plot of mouse
  weight vs avg observed tumor volume


#Results
A few findings from this analysis are; mouse l509 tumor volume drastically reduced as the timepoint increased while being treated with Capomulin.  Average tumor volume appears to increase the heavier the mouse is.  The correlation between mouse weight and the average
tumor volume is 0.84.  

#Usage
Navigate to the repo direcotry and launch a jupyter notebook via "python -m notebook" and open the "pymaceuticals_analysis.ipynb" file. Once open, all dependencies are imported so you just need to run each cell in the notebook. 

#License
Specify the license under which your project is released Apache.
