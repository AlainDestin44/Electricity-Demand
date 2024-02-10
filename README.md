# Wind Power Generation Analysis (2014)

## Overview
This project involves the analysis of wind power generation data collected at 15-minute intervals throughout the year 2014. The objective is to gain insights into the patterns and trends of wind power generation, which are crucial for renewable energy planning and management.

## Folder Structure
- **Notebooks:** Contains Jupyter notebooks used for data analysis and visualization.
- **Reports:** Includes detailed reports summarizing the analysis findings and insights.
- **Data:** Contains the dataset used for analysis.
- **Requirements.txt:** Lists all dependencies required to run the analysis scripts.

## Analysis Steps
1. **Data Preprocessing**
   - Reading the dataset
   - Assessing and handling missing values using linear interpolation
   - Changing the index to datetime for time-based analysis

2. **Data Analysis**
   - Plotting the time series to visualize trends and patterns
   - Plotting the autocorrelation series to identify temporal dependencies
   - Exploring seasonal trends and monthly variations in wind power generation
   - Analyzing average daily and weekly energy generation profiles
   
3. **Hypothesis Testing**
   - Testing the similarity in energy generation between weekends and weekdays using hypothesis testing
   
4. **Modeling and Forecasting**
   - Conducting persistence forecasting to benchmark forecasting accuracy
   - Evaluating Mean Absolute Error (MAE) for different forecast horizons
   
## Conclusion
The analysis provides valuable insights into seasonal patterns, temporal dependencies, and weekly energy demand cycles in wind power generation. These insights are crucial for renewable energy planning and management, informing decision-making processes and facilitating the development of robust forecasting models.
