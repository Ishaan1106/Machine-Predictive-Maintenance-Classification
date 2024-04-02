# Machine Predictive Maintenance Classification

## Description
This project aims to predict machine failures using a dataset containing information about machine failures and maintenance logs. The dataset includes features such as machine type, air temperature, process temperature, rotational speed, torque, tool wear time, and failure type.

## Dataset
The dataset contains the following columns:
- UID: A unique identifier for each observation.
- Product ID: A unique identifier for each product.
- Type: The type of machine.
- Air Temperature [K]: The air temperature in Kelvin.
- Process Temperature [K]: The process temperature in Kelvin.
- Rotational Speed [rpm]: The rotational speed of the machine in revolutions per minute.
- Torque [Nm]: The torque of the machine in Newton-meters.
- Tool Wear [min]: The amount of time the tool has been in use in minutes.
- Target: A binary variable indicating whether the machine is likely to fail or not.
- Failure Type: The type of failure that occurred.

## Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- missingno
- plotly

## Analysis
The analysis includes:
- Loading data into a pandas DataFrame.
- Calculating basic statistical measures for each column.
- Handling missing values.
- Grouping data by machine type and calculating average air temperature.
- Determining the most common failure type.
- Calculating the range of tool wear time.
- Finding the mode of the air temperature distribution.
- Counting the unique number of each failure type.
- Calculating the 75th percentile of the air temperature.

## Data Visualization
The visualization includes:
- Visualizing the proportion of each failure type using a pie chart.
- Using a histogram and KDE plot to visualize tool wear time across machine types.
- Using a scatterplot to visualize the correlation between rotational speed and torque.
- Creating a heatmap to visualize the correlation between all numeric features.
- Visualizing the distribution of unique values in the 'Type' column using a bar chart and a pie chart.
- Using a scatterplot to visualize the relationship between air temperature and process temperature.
- Using a countplot to visualize the number of occurrences of each failure type.
- Using a histogram and KDE plot to visualize the distribution of air temperature.
- Using a displot to visualize the distribution of rotational speed across different machine types.

## Data Manipulation
The data manipulation includes:
- Converting 'Tool wear [min]' column from integer to float for more precise measurements.
- Rearranging columns in the DataFrame to bring 'Tool wear [min]' next to 'Type' for easier comparison and analysis.

## How to Run
1. Clone this repository.
2. Install the necessary libraries mentioned above.
3. Run the Jupyter notebook.

