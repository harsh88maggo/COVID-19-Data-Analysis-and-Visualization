# COVID-19 Data Analysis Across India

## Project Overview
This project analyzes COVID-19 data across India to provide insights into the distribution and trends of COVID-19 cases, recovery rates, and the impact across different age groups and regions. The dataset includes detailed statistics about confirmed cases, recoveries, and active cases in various states of India. This analysis helps in understanding patterns of the disease’s spread, recovery, and geographical distribution.

## Data Sources
- **Covid.csv**: Contains COVID-19 statistics, including confirmed cases, recoveries, and deaths across different states of India. This data is sourced from [PRS India](https://prsindia.org/covid-19/cases/download).
- **AgeGroupDetails.csv**: This dataset includes details about COVID-19 cases across different age groups.
- **active_cases_2020-07-17_0800.csv**: Contains data on active COVID-19 cases in Indian states on July 17, 2020. The data is sourced from an external GitHub repository.

## Objective
- To analyze COVID-19 recovery rates across Indian states.
- To explore the distribution of COVID-19 cases by age group.
- To visualize the geographical distribution of active COVID-19 cases across India using choropleth maps.

## Key Features
1. **Number of Patients Recovered Across States**: Visualizes the number of patients recovered across Indian states using a bar chart.
2. **COVID-19 Cases by Age Group**: Displays both a bar chart and a pie chart to show the distribution of COVID-19 cases by age group.
3. **Active COVID-19 Cases Across States**: A choropleth map that visualizes active COVID-19 cases in each Indian state.

## How to Run the Project

### Requirements
Ensure you have the following Python packages installed:

- `pandas`: For data manipulation and analysis.
- `plotly`: For creating interactive visualizations.
- `matplotlib`: For additional plotting and visualization.

You can install the required packages by running the following command:

```bash
pip install -r requirements.txt
```
## Running the Code

### Download the required datasets:
- **Covid.csv**: Download from [PRS India](https://prsindia.org/covid-19/cases/download) and place it in the project directory.
- **AgeGroupDetails.csv**: Ensure the file is in the project directory or update the path accordingly.
- **active_cases_2020-07-17_0800.csv**: This is fetched directly from the provided URL in the script.

### Run the script to generate the visualizations:
- Execute the Python script in the Jupyter notebook provided or command line interface.

### The output includes interactive visualizations:
- A bar chart showing the recovery rates across states.
- A subplot combining a bar chart and a pie chart of COVID-19 cases by age group.
- A choropleth map visualizing active COVID-19 cases across Indian states.

## Visualizations
- **Patients Recovered Across States**: A bar chart highlighting states with the most recoveries.
- **COVID-19 Cases by Age Group**: A bar chart and pie chart depicting the total cases and distribution by age group.
- **Active Cases Across States**: A choropleth map displaying the intensity of active cases in each state.
