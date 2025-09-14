Global Deforestation & Carbon Emissions Analysis (2001–2022)
This project investigates global deforestation trends from 2001 to 2022 and analyzes their impact on net carbon emissions. Using datasets from Kaggle, the analysis identifies key drivers of carbon emissions and highlights the most affected regions.
What’s Inside
Data cleaning, preprocessing, and merging of multiple datasets
Exploratory Data Analysis (EDA) with detailed visualizations
Analysis of tree cover loss, gain, and net forest change
Identification of top countries contributing to deforestation
Factor analysis to determine the most significant contributors to carbon emissions
Baseline and exploratory models to predict net carbon emissions
Dataset
Source: Global Forest Data (2001–2022)
Files used:
Country tree cover loss.csv
Country carbon data.csv
Subnational 1 tree cover loss.csv
Subnational 1 carbon data.csv
Progress
Week 1: Data Exploration
Loaded and cleaned datasets
Checked column names and unique values
Generated visualizations of forest loss
Identified countries with highest deforestation
Week 2: Preprocessing & Baseline Model
Merged tree cover loss and carbon emissions datasets
Converted wide format to long format for yearly analysis
Handled missing values and scaled numeric features
Trained a simple linear regression model to predict carbon emissions
Split data into train and test sets
Evaluated baseline model using Mean Squared Error (MSE) and R² score
Week 3: Advanced Analysis & Visualization
Explored trends in forest gain and loss
Created visualizations for top contributors to global deforestation
Computed net forest change for each country
Week 4: Factor Analysis & Key Findings
Identified the most important factors influencing net carbon emissions
Analyzed correlations between deforestation and carbon emissions
Highlighted key patterns and trends across countries and years
Key Findings
Certain factors such as tree cover loss, industrial activity, and land use changes have a strong correlation with net carbon emissions
Top deforesting countries contribute disproportionately to global carbon emissions
Visualizations and analyses can guide sustainable policies and mitigation strategies
How to Run
Clone the repository
Install dependencies:
pip install -r requirements.txt
Open notebooks in Kaggle or Jupyter and execute cells sequentially
Future Work
Expand dataset with more recent and granular data
Build predictive models using machine learning to forecast carbon emissions
Create interactive dashboards for visual exploration of deforestation trends
Author
Sahaj Sharma
