# Matplotlib Homework - The Power of Plots

Overview: The jupyter notebook named Pymaceuticals in the Pymaceuticals folder reads csv files in the data folder (drug treament on tumors in mice) and completes the analysis described below.

-Three observations from the data are included at the top of the notebook.
-Data is checked for duplicate mouse IDs and any data associated with that/those mouse IDs are removed.
-A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen is included (for all data).
-Two identical bar plots are generated using Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that show the total number of measurements taken for each treatment regimen throughout the course of the study.
-Two identical pies charts are generated using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
-The the final tumor volume of each mouse is calculated across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
-Quartiles and IQR of final tumor volume are calculated and for all four treatment regimens. (outliers were not quantitatively identified)
-A boxplot of the final tumor volume was generated using pandas box plot (not matplotlib). An updated version would appropriately format the data so it could be used in matplot lib.
-A mouse that was treated with Capomulin was chosen and  a line plot of tumor volume vs. time point was generated for that mouse.
-A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen was generated.
-The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment was generated with a linear regression model. 
