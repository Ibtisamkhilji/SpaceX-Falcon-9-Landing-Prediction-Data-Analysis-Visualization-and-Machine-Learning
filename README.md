# SpaceX Falcon 9 Landing Prediction: Comprehensive Data Analysis, Visualization, and Machine Learning Project

## Description
This repository showcases a complete data science project focused on predicting the success of SpaceX Falcon 9 rocket landings. The project incorporates data collection, data wrangling, exploratory data analysis, interactive visualizations, and machine learning modeling to uncover insights about SpaceX's reusable rocket technology.

With the growing significance of cost-effective space travel, SpaceX’s ability to reuse the first stage of its Falcon 9 rockets has made it a market leader. This project explores the factors influencing landing success, allowing for predictive analytics that can be valuable for competitors and researchers.

## Project Workflow
The workflow of the project is divided into the following key phases:
1. **Data Collection**:
   - Using SpaceX’s RESTful API to fetch rocket launch data, including launch dates, payloads, and landing outcomes.
   - Web scraping Falcon 9’s historical launch records from Wikipedia using BeautifulSoup and Requests.
     
2. **Data Wrangling**:
   - Cleaning and preprocessing raw datasets to make them suitable for analysis.
   - Removing duplicate records, handling missing values, and standardizing formats.

3. **Exploratory Data Analysis (EDA)**:
   - Conducting SQL-based analysis to query data for trends.
   - Visualizing patterns using Matplotlib and Seaborn to identify correlations and key variables influencing landing success.

4. **Interactive Visualizations**:
   - Building interactive geographical maps using Folium to display launch sites and trajectories.
   - Developing a real-time dashboard using Plotly Dash for dynamic data exploration.

5. **Machine Learning**:
   - Implementing classification models to predict whether the first stage will land successfully.
   - Tuning and evaluating models for optimal performance.

## Repository Contents
- **`1_Data Collection API.ipynb`**: Notebook demonstrating how SpaceX Falcon 9 data was fetched using SpaceX's API.
- **`2_Web Scrapping.ipynb`**: Notebook showing web scraping methods to collect historical launch data from Wikipedia.
- **`3_Data Wrangling.ipynb`**: Notebook outlining the data cleaning and preprocessing steps.
- **`4_EDA SQL.ipynb`**: SQL-based queries to analyze and extract insights from the cleaned dataset.
- **`5_EDA_Matplotlib.ipynb`**: Visualization of key trends and correlations using Matplotlib and Seaborn.
- **`6_Interactive Visual Analysis Using Folium.ipynb`**: Interactive map visualization of launch sites using Folium.
- **`7_Build an Interactive Dashboard with Ploty Dash - spacex_dash_app.py`**: Python script to create an interactive dashboard for real-time data exploration using Plotly Dash.
- **`8_ML Predictions.ipynb`**: Implementation of machine learning models to predict Falcon 9 landing success.

## Technologies Used
- **Languages and Libraries**:
  - Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly Dash
  - Web Scraping: BeautifulSoup, Requests
  - SQL for querying and analysis
  - Folium for interactive map visualizations

- **APIs**:
  - SpaceX RESTful API

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/ibtisamkhilji/spacex-falcon9-landing-prediction.git
2. Navigate to the folder:
   ```bash
   cd spacex-falcon9-landing-prediction
3. Install dependencies: Ensure you have Python 3.9+ and install the required packages:
   ```bash
   pip install -r requirements.txt
5. Run the notebooks sequentially to reproduce results.
6. Execute the dashboard app script (spacex_dash_app.py) to launch the interactive dashboard:
   ```bash
   python spacex_dash_app.py

## Insights and Key Learnings:
The success of Falcon 9's first-stage landings significantly influences the cost of rocket launches.
Machine learning models achieved a high accuracy in predicting landing outcomes based on launch data.
Interactive dashboards provide dynamic insights, enabling stakeholders to explore data more effectively.

## Future Scope:
Extend the dashboard to include predictive capabilities.
Incorporate data from other rocket providers for comparative analysis.
Explore deep learning techniques for improved predictions.
## Acknowledgements:
Data collected from SpaceX API and Wikipedia.
Libraries and tools provided by the Python community.


