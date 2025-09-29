# Exploratory-Data-Analysis-EDA-

📊 Objective
The primary objective was to extract meaningful insights from the dataset through statistical summarization and data visualization, serving as the critical first step before building a machine learning model.

🛠️ Tools and Libraries Used
Programming Language: Python

Core Libraries:

Pandas: Used for data loading, cleaning, manipulation, and statistical summarization (e.g., .info(), .describe(), .value_counts()).

Matplotlib & Seaborn: Used for generating visualizations (histograms, boxplots, scatterplots, heatmaps) to uncover distributions and relationships.

📋 Repository Contents
Untitled4.ipynb: The main Jupyter Notebook containing all the Python code, statistical outputs, visualizations, and detailed observations.

archive (5).zip: The original compressed dataset file.

train.csv: The extracted, clean data file used for the analysis.

✨ Key Findings and Trends (Summary of Insights)
The Exploratory Data Analysis revealed several strong relationships between passenger features and the target variable (Survived):

Gender (Sex) is the Strongest Predictor:

Trend: Females had a significantly higher survival rate than males, illustrating the "women and children first" protocol.

Socio-Economic Status (Pclass) is Critical:

Trend: There is a strong inverse relationship between Passenger Class (Pclass) and survival. 1st class passengers had the highest survival rate, followed by 2nd, with 3rd class having the lowest.

Age Distribution:

Trend: Very young children (under 10) had a higher chance of survival. The majority of casualties were concentrated in the young to middle-aged adult bracket.

Fare and Class Correlation:

The Correlation Heatmap showed a strong negative correlation between Pclass and Fare (higher class number means lower fare). This confirms that wealth/privilege (represented by Fare and Pclass) was highly influential on survival.

Missing Data:

The .info() output confirmed significant missing data in the Cabin column (which may require dropping or advanced imputation) and the Age column (which requires imputation, typically using the mean or median).

