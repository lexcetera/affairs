# Exploring Factors Affecting Extramarital Affairs

An exploratory data analysis project to determine which factors may influence extramarital affairs. The project uses Python, pandas, and Jupyter notebooks to explore the dataset, clean the data, and uncover patterns and insights.

The dataset was obtained from Kaggle under "Fair's Affairs Dataset."

Chong, C. (n.d.). *Fair’s Affairs dataset* [Data set]. Kaggle. https://www.kaggle.com/datasets/clarkchong/fairs-affairs-dataset

# Correlation Skewness Table

| Feature       | abs_correlation | Effect   |
|---------------|----------------|----------|
| happiness     | 0.279512       | negative |
| yearsmarried  | 0.186842       | positive |
| religiousness | 0.144501       | negative |
| age           | 0.095237       | positive |
| occupation    | 0.049612       | positive |
| education     | 0.002437       | negative |



# The Correlation Plot

![Correlation Plot](plots/correlation_plot_image.png)

# The Findings

Based on the exploratory analysis of the Fair’s Affairs Dataset, several factors were examined for their association with the likelihood of extramarital affairs. The strongest relationships were observed with happiness (negative) and years married (positive), suggesting that lower happiness and longer marriages led to a higher likelihood of engaging in extramarital affairs. Religiousness also had a negative effect suggesting that more religious people tend to be faithful. Age, on the other hand, showed moderate (positive) influence, while occupation and education had minimal effect. Overall, the analysis highlights that personal satisfaction and marital duration are key factors associated with extramarital behavior.