# Time Series Analysis: Italian Solar Generation and Load Data (2016)

## Project Overview

This project focuses on analyzing time series data for Italy's electrical load and solar power generation throughout the year 2016. The initial setup involves loading and performing an initial exploration of the dataset to understand patterns in energy consumption and renewable energy production.

## Project Structure

The project is organized as a Jupyter Notebook (`Projects 1.ipynb`) containing:

1. **Data Loading**: Importing the dataset from a CSV file.
2. **Initial Data Exploration**: Displaying the first few rows of the data to understand its structure.
3. **Data Visualization**: Plotting the time series data to visualize trends (implied by the import of `matplotlib`).

## Dataset

The dataset used is: `TimeSeries_TotalSolarGen_and_Load_IT_2016.csv`

It contains the following columns:

- **utc_timestamp**: The timestamp of the recording in UTC format (hourly intervals).
- **IT_load_new**: The total electrical load (demand) in Italy at the given timestamp (in MW).
- **IT_solar_generation**: The total solar power generation in Italy at the given timestamp (in MW).

### Example Data (First 5 Rows)

| utc_timestamp       | IT_load_new | IT_solar_generation |
|---------------------|-------------|---------------------|
| 2016-01-01T00:00:00Z| 21665.0     | 1                   |
| 2016-01-01T01:00:00Z| 20260.0     | 0                   |
| 2016-01-01T02:00:00Z| 19056.0     | 0                   |
| 2016-01-01T03:00:00Z| 18407.0     | 0                   |
| 2016-01-01T04:00:00Z| 18425.0     | 0                   |

## Requirements

To run this notebook, you need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib jupyter 
