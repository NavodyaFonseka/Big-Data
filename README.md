# Big-Data
Using Big Data Techniques to interpret Global Terrorism dataset

This assignment will investigate and analyze global terrorism patterns using the Global Terrorism Database (GTD), one of the most extensive open-source datasets on terrorist incidents in the world. The GTD provides detailed information on over 180,000 terrorist occurrences from various countries and decades, including characteristics such as attack type, target type, weapon category, fatalities, geographic location, and so on. The breadth and richness of this dataset make it ideal for big data analysis and advanced visualization techniques.
This research uses analytical methods and big data technology to uncover significant trends and hotspots in terrorist activity, evaluate temporal and spatial distributions, and investigate the human effects of terrorism around the world. The ultimate goal is to demonstrate how real-world data can be transformed into actionable knowledge that supports evidence-based decision-making in global security and policy development.


Plan of Analysis
The steps below cover the entire analytical plan:
•	Phase 1: Data Preparation
o	Imported essential Python libraries such as dask, pyspark, pandas, numpy, matplotlib, seaborn, plotly, sklearn, nltk, and folium.
o	Uploaded the GTD dataset and inspected its structure and data types.
o	Selected key variables relevant to attack characteristics, geography, time, weapons, casualties, and group affiliations.
o	Feature Engineering to derive new features.

•	Phase 2: Data Preprocessing
o	Numerical Variables: Handle missing values, remove duplicates, and detect/treat outliers.
o	Categorical Variables: Normalize text fields (e.g., trim whitespace, standardize case).

•	Phase 3: Descriptive Analytics
o	Summary Statistics: Generate descriptive statistics to understand distributions and central tendencies.
o	Exploratory Data Analysis (EDA):
	Charts: Use line charts (trends over time), bar/pie charts (attack types, target types), and choropleth maps (regional distribution), etc.
	Interactive Visuals: Employ Plotly and Folium for dynamic maps and drill-down visuals.

•	Phase 4: Advanced Data Analysis
o	Clustering & Incident Profiling: Use K-Means to identify attack patterns and incident clusters.
o	Temporal Trend Analysis & Forecasting: Analyze attack frequency over time and build forecasting models for future predictions.
o	Risk Scoring & Severity Index: Compute and classify incidents into risk levels using severity scores derived from casualties and attack type.
o	Hotspot Analysis: Identify spatial hotspots using latitude-longitude maps and heatmaps.
o	Target and Perpetrator Profiling: Analyze and visualize most attacked targets and most active terrorist groups.
o	Severity Analysis: Understand factors contributing to high-fatality events 
o	Textual Analysis: Use NLP techniques (tokenization, word clouds) on incident summaries to extract keywords and common attack narratives.
o	Predictive Modeling:
	Model 1: Predict whether an attack is deadly (killed > 0)
	Model 2: Predict whether an attack is a suicide attack.
	Model 3: Predict whether an attack was successful.
	Models used: Random Forest, Gradient Boosting, Logistic Regression.


Please find all scripts and code files (both .ipynb and .html) in the Google Drive folder.

https://drive.google.com/drive/folders/1xhzjHZuBPdfJnDJZEPMc0TElC1S5PlVm?usp=sharing
