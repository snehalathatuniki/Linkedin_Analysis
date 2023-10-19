# LinkedIn Data Analysis
![image](https://github.com/snehalathatuniki/Linkedin_Analysis/assets/43737913/66d24fd5-3926-4e2f-b353-d3d9b67eead6)

This repository contains the code, data, and visualizations associated with the analysis of LinkedIn connections. The primary goal is to derive insights from the connections' data, understand the growth of the network over time, and identify patterns related to the companies and positions of the connections.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
3. [Analysis and Visualizations](#analysis-and-visualizations)
4. [Dependencies](#dependencies)
5. [Usage](#usage)

## Project Overview
LinkedIn provides an option to download an archive of your data. This project takes that data as input and offers a detailed analysis of various aspects of the professional network. We aim to understand:

- The growth trajectory of the LinkedIn network.
- Distribution of connections across companies and positions.
- Duration since each connection was made.
- Prominence of Companies
  
## Data Cleaning and Preparation
The data cleaning process involves:

- Removing duplicate entries.
- Handling missing values.
- Converting date fields to a consistent format.
- Deriving metrics like connection duration.

More details can be found in the Jupyter Notebook.

## Analysis and Visualizations
The analysis phase is categorized into:

1. **Time Series Analysis**: Understanding the growth of the LinkedIn network over time.
2. **Company & Position Analysis**: Insights into the top companies and positions prevalent in the network.
3. **Connection Duration Analysis**: A histogram showcasing the duration since each connection was made.

Visualizations are generated using Python libraries, and advanced dashboards can be found in the provided Tableau workbook.

## Dependencies
- Python 3.9.13
- Pandas
- Matplotlib

## Usage
1. Download your [LinkedIn data archive](https://www.linkedin.com/help/linkedin/answer/a1339364/downloading-your-account-data?lang=en-us&intendedLocale=en) from the LinkedIn settings page.
2. Place the CSV in the `data/` directory.
3. Run the provided Jupyter Notebook or Python script for analysis.
