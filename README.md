Exploratory Data Analysis (EDA) on a Wine Quality Dataset
This project performs Exploratory Data Analysis (EDA) on a wine dataset to examine the potential relationships between various chemical properties and wine quality ratings.

Dataset
The dataset used in this project is called 13-WineQT.csv and contains red wine samples with various chemical properties (e.g., fixed acidity, volatile acidity, alcohol content) and quality scores.

Libraries Used
The following Python libraries were used to perform the analysis:

pandas (For data manipulation and analysis)

numpy (For numerical operations)

matplotlib.pyplot (For data visualization)

seaborn (For advanced data visualization)

Analysis Steps
The analysis process included the following key steps:

Loading and Overview of the Dataset: The content, number of rows, and number of columns of the dataset were checked.

Data Structure Examination: Column names, data types, and null values were checked to confirm that the dataset was clean.

Statistical Summary: Basic statistical information such as mean, standard deviation, minimum, and maximum values of the data were examined.

Identification of Duplicate Data: Duplicate rows in the dataset were identified and removed.

Correlation Analysis: The correlations between the features in the dataset were visualized with a heatmap to examine which features were related to each other or to wine quality. It was observed that alcohol content had a high positive correlation with wine quality.

Distribution Plots: The distribution of each feature was visualized with kernel density plots (kdeplot), colored by wine quality, to discover potential features affecting wine quality.
