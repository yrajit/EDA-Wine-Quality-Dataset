**Overview**
In this project, I performed Exploratory Data Analysis (EDA) on the Wine Quality dataset using Python. The aim was to understand the dataset, 
check how different features are distributed, and see what factors may affect wine quality.

**Dataset**
The dataset contains 4,898 records and 12 numerical features. There are no missing values. The target variable is quality, which represents the wine rating.

**Tools Used**
I used Python along with Pandas and NumPy for data handling, and Matplotlib and Seaborn for visualization. The analysis was done in Jupyter Notebook.

**worked**
I started by loading and checking the dataset. Then I calculated basic statistics like mean, median, and mode. After that, 
I analyzed the distribution of features using plots and checked skewness. I also focused on how the quality variable is distributed.

**Key Observations**
I found that fixed acidity is roughly normally distributed, while volatile acidity is skewed to the right.
Most wines fall in the quality range of 5 to 7, and the most common quality score is 6.

**How to Run**
git clone https://github.com/yrajit/Wine-Quality-EDA.git
cd Wine-Quality-EDA
pip install -r requirements.txt
jupyter notebook

**Conclusion**
This analysis helped me understand the dataset better and gave useful insights into wine quality. 
 It also builds a base for applying machine learning models in the future.
