# Meddlesome is a data frame interpreter to get a visual first look 

x = your dataframe as a .csv
info(x)
-outputs a list of NaN counts by feature 
-plots NaN occurences visually, specifically the axes are features by index. 
-plots correlation two matrixes via seaborn heatmaps one for numeric values, one for non-numeric values that have been ordinal-encoded
-saves the above plots in directory as PlotOfNaNinDF.png and correlation_matrix_non_numeric.png

![NaN](/PlotOfNaNinDF.png)
![CorrelationMatrix](/correlation_matrix_num_and_non_num.png)

Dependencies:
pandas
numpy
seaborn
matplotlib
catefory_encoders
