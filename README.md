# matplotlib-challenge
This is Kokila's Matplotlib homework.

* Combine the Mouse metadata and Study results data into a single dataset.
* Getting the duplicate mice by ID number that shows up for Mouse ID and Timepoint. 
* Get all the data for the duplicate mouse ID.
* Create a clean DataFrame by dropping the duplicate mouse by its ID.
* Checking the number of mice in the clean DataFrame.

## Summary Statistics
* Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen.
* Use groupby and summary statistical methods to calculate the following properties of each drug regimen: mean, median, variance, standard deviation, and SEM of the tumor volume.
* Assemble the resulting series into a single summary dataframe.

* Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen.
* Using the aggregation method, produce the same summary statistics in a single line.

* Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen.

## Bar and Pie Charts
* Using the aggregation method, produce the same summary statistics in a single line.
* Generate a bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot.

* Generate a bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot.
* Generate a pie plot showing the distribution of female versus male mice using pyplot

## Quartiles, Outliers and Boxplots
* Calculate the final tumor volume of each mouse across four of the treatment regimens:     Capomulin, Ramicane, Infubinol, and Ceftamin.
* Start by getting the last (greatest) timepoint for each mouse
* Merge this group df with the original dataframe to get the tumor volume at the last timepoint.

* Put treatments into a list for "for loop" (and later for plot labels).
* Create empty list to fill with tumor vol data (for plotting).
* Locate the rows which contain mice on each drug and get the tumor volumes using for loop.
* Calculate the IQR and quantitatively determine if there are any potential outliers.
* Determine outliers using upper and lower bounds.
* Generate a box plot of the final tumor volume of each mouse across four regimens of interest.

## Line and Scatter Plots
* Generate a line plot of tumor volume vs. time point for a mouse treated with Capomulin.
* a mouse treated with Capomulin : mouse ID = "i557"
* Make variables to plot
* Plot our line that will be used to.

* Generate a scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen.
* Get average tumor volume.
* Create scatterplot.

## Correlation and Regression
* Calculate the correlation coefficient and linear regression model 
* for mouse weight and average tumor volume for the Capomulin regimen
* Equations for correlation and regression
