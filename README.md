# Score_test_by_one_way_ANOVA

This project performs an ANOVA (Analysis of Variance) test on a sample dataset and visualizes the results. The dataset contains three segments, and the goal is to determine if there is a significant difference between the means of these segments.

## Dependencies
pandas
matplotlib
scipy

## Dataset
The dataset contains 25 observations (rows) and 3 segments (columns) named Segment_A, Segment_B, and Segment_C. Each observation represents a value for each of the three segments.

## Methodology
Load the dataset using pandas.
Perform an ANOVA test using the f_oneway function from the scipy.stats library.
Determine if there is a significant difference between the means of the segments based on the p-value.
Calculate the means and standard deviations for each segment.
Visualize the means and standard deviations with a bar plot, including error bars for the standard deviations.
Display the ANOVA result, F-statistic, and p-value as text on the plot.
