# Data Visualization Final Project
[The Dataset we are using](https://www.kaggle.com/datasets/theforcecoder/wind-power-forecasting?datasetId=796750)
<br/>
# Please look at what each file depends on before running our code!!!
<br/>

| **File Name**                     	| **Description**                                                                                                      	| **Depends On**     	|
|-----------------------------------	|----------------------------------------------------------------------------------------------------------------------	|--------------------	|
| Analysis with Bearing Shaft.ipynb 	| Plots Active Power and Bearing Shaft Temperature over the entire dataset                                             	| None               	|
| Analysis.ipynb                    	| From the cleaned data, plot Average Power over time, Hex Bin Plots, and Regression Plots                             	| DataCleaning.ipynb 	|
| 1_Data Exploration.ipynb            	| Our Initial File for data exploration, used for determining what to do in the data cleaning section                  	| None               	|
| 2_DataCleaning.ipynb                	| Generates a cleanData.csv file for use in other files                                                                	| None               	|
| GenerateBoxPlots.ipynb            	| Generates the box plots used to show outliers and distributions (After cleaning)                                     	| DataCleaning.ipynb 	|
| GenerateHistograms.ipynb          	| Generate the histograms from cleaned data                                                                            	| DataCleaning.ipynb 	|
| GenerateTimeGraphs.ipynb          	| Generate the bar and line charts for active power by month and day.                                                  	| DataCleaning.ipynb 	|
| GenerateUnique.ipynb              	| Generate random unique graphs that we found useful during data exploration and the presentation                      	| DataCleaning.ipynb 	|
| NullCountVisualization.ipynb      	| Generate the visualizations for the null counts, along with show the month by month null percents for each attribute 	| None               	|

Some graphs are kept in notebooks, but the majority are autogenerated and saved as a png in their corresponding directory