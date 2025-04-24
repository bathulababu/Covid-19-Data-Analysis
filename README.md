# COVID-19 Data Analysis

This project involves analyzing the COVID-19 dataset to gain insights into the spread and impact of the virus. The analysis includes data processing, visualization, and exploring relationships between COVID-19 data and the worldwide happiness report.

## Project Description

The goal of this project is to understand the trends and patterns of COVID-19 confirmed cases. By analyzing the provided dataset, we aim to extract meaningful information and visualize the impact of the pandemic.

## Data

The dataset used in this project includes:

-   `covid19_Confirmed_dataset.csv`: Contains data related to COVID-19 confirmed cases.
-   `covid19_deaths_dataset.csv`: Contains data related to COVID-19 deaths.
-   `worldwide_happiness_report.csv`: Contains data on the worldwide happiness report.

## Methodology

1.  **Data Loading and Exploration**:
    -   Loading the COVID-19 confirmed dataset using pandas.
    -   Displaying the first few rows of the dataset.
    -   Checking the shape of the dataframe.
2.  **Data Aggregation**:
    -   Aggregating the COVID-19 data by country/region to summarize the confirmed cases.
3.  **Data Visualization**:
    -   Plotting the data to visualize trends and patterns (e.g., total confirmed cases over time for specific countries).
4.  **Happiness Report Analysis**:
    -   Loading the worldwide happiness report.
    -   Joining the COVID-19 data with the happiness report to explore potential correlations.
    -   Visualizing the relationship between happiness scores and COVID-19 impact.
5.  **Correlation Analysis**:
    -   Calculating and visualizing correlations between relevant features.
    -   Using regression plots to show the relationship between variables.

## Libraries Used

-   pandas
-   numpy
-   seaborn
-   matplotlib.pyplot

## Usage

To replicate this analysis:

1.  Ensure you have the required libraries installed:

    ```bash
    pip install pandas numpy seaborn matplotlib
    ```

2.  Place the datasets (`covid19_Confirmed_dataset.csv`, `covid19_deaths_dataset.csv`, `worldwide_happiness_report.csv`) in the same directory as the notebook or adjust the paths accordingly.
3.  Run the Jupyter Notebook (`covid-19-data-anaysis.ipynb`) to execute the code and reproduce the results.

## Files

-   `covid19_Confirmed_dataset.csv`: Dataset containing confirmed COVID-19 cases.
-   `covid19_deaths_dataset.csv`: Dataset containing COVID-19 deaths data.
-   `worldwide_happiness_report.csv`: Dataset containing worldwide happiness report.
-   `covid-19-data-anaysis.ipynb`: Jupyter Notebook containing the code and analysis.

## Key Insights

The analysis provides insights into:

-   Trends in COVID-19 confirmed cases.
-   Potential relationships between COVID-19 data and happiness scores.
-   Correlations between different variables.

## Author

\[Naveen Babu Bathula]
