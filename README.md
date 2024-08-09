# Feature Engineering for Layover Assignment in Flight Data

## Project Description
This project focuses on the assignment of layover values within a dataset of flight routes. The primary goal is to enhance the dataset by feature engineering, specifically by calculating and assigning layover times using a newly created variable, `total_air_time`. The project leverages Python libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn` for data manipulation, analysis, and visualization.

## Layover Assignment
Layovers are assigned by calculating the difference between the total air time of consecutive flight segments (total_dur). The idea is to determine how much time a flight spends in the air by creating a bench of air time by analyzing the non-stop flights. The newly created `total_air_time` variable serves as the foundation for these calculations. By analyzing this data, the project assigns a specific layover duration to each stop along the flight route, providing valuable insights into travel patterns and potential delays.

## Key Features & Code Explanation

* Data Importation and Initialization: The project begins by importing necessary Python libraries and loading the flight data.

* Feature Engineering: The core of the project focuses on creating the total_air_time variable and assigning layover values based on this metric.

* Data Visualization: Utilizes matplotlib and seaborn to visualize the results, including the distribution of layover times.

* Database Integration: The use of sqlite3 for database operations, allowing for efficient data handling and storage.

## Dataset Description

The dataset used in this project includes flight routes with several variables such as start, stop, and destination locations. The feature engineering process involves calculating layover times based on the total air time of different flight segments.








