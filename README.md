# Problem Statement
We'll continue working with the weather dataset used in the previous project. We will further analyze the dataset and identify any trend using the Matplotlib library. The index of the dataset is the Date/Time instance at a gap of one hour in the year 2012.

About the Dataset-
Snapshot of the Dataset:

Data_snapshot

# Features:
Name	Description
Date/Time	Date & Time for each hour in the year 2012.
Temp(C)	Exact temperature at a given time.
Dew Point Temp(C)	Dew Point Temp at a given time. It is the temperature to which air must be cooled to become saturated with water vapor.
Rel Hum (%)	Relative Humidity at a given time.
Wind Spd (km/h)	Wind Speed in km/h at a given time.
Visibility (km)	Visibility in km at a given time.
Stn Press (kPa)	Station Pressure observed at that time.
Weather	Weather at a given time.

# -------------------------------------------------------------------------
# instructions

# Task
# Instructions
Different functions that you would require to define for this project has been mentioned in the code block. All the parameters and the task, a function would do, have been mentioned there.

Load the weather_2012 data csv file and store it in weather_df variable. The path of the dataset has been stored in the variable path for you.

Check the categorical and numerical variables.

With the help of a line chart, visualize the monthly trend in the temperature. Call the line_chart() to do the same.
You should get a trend similar to the below.

image1

Visualize the distribution of the different features of your interest. Call the plot_categorical_columns() and plot_cont() to do the plot.
The distribution of the numerical columns should be similar to below.
image2

Groupby the data by Weather and plot the graph of the mean Visibility (km) during different weathers. Call the function group_values() to plot the graph.
The mean Visibility (km) during different Weathers is shown by the below graph.
image3


# for query contact: raunakagarwal274@gmail.com
