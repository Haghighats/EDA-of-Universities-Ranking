# **Universities Ranking:** <br>
This project delves into a dataset containing information about 1000 top universities around the world. Here's a breakdown of the data cleaning and exploratory data analysis (EDA) steps employed:<br>
## **Data Cleaning:** <br>
•	Missing Value Handling: Replaced non-standard missing value indicators ("-") with standard NaN (Not a Number) values in specified columns. Subsequently, appropriate methods were used to address these missing values based on the distribution of missing data.<br>
•	Detecting Duplicates: No duplicates were found in this dataset.<br>
•	Outlier Detection and Treatment: Identified rows containing ">1000" values. To prevent errors during data manipulation and visualization, these outliers were replaced with a consistent value (e.g., 1001) while acknowledging their presence in the data description (consider adding a note in your code or documentation).<br><br>
## **Exploratory Data Analysis (EDA):** <br>
### **•	Univariate Analysis:** <br>
o	Investigated the distribution of each feature using techniques like histograms, boxplots, and descriptive statistics to understand the central tendency, spread, and potential skewness of the data.<br>
o	Identified the top 10 values for each feature to show best .<br>
### **•	Bivariate Analysis:** <br>
o	Constructed a heatmap to visualize the pairwise correlations between features, providing insights into potential relationships between university ranking and other attributes.<br>
### **•	Multivariate Analysis:** <br>
o	Created a pairplot to visualize the relationships between multiple features simultaneously, offering a more comprehensive view of the data structure. <br>
These steps provide a foundation for deeper analysis, feature engineering, and potential modeling tasks. You can find the code used for this project in this repository.
