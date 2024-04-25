### DTSC-610-Exploration-of-Iris-Dataset

* In this exploration of the classic Iris dataset, we utilized various Python libraries including Pandas, NumPy, Matplotlib, and Scikit-Learn to load, manipulate, analyze, visualize, and model the data.

* We loaded the Iris dataset using Pandas' read_csv function and displayed the first five rows of the dataset to gain an overview. By using len() and .dtypes, we identified that the dataset consists of four features with numeric data types.

* A new column was added to the dataset to calculate the petal area, obtained by multiplying the petal length by the petal width. We verified the addition of this column by printing out the first few rows of the DataFrame.

* Using NumPy, we calculated the mean and standard deviation of the sepal lengths, converting the relevant column of the DataFrame to a NumPy array and applying NumPy's statistical functions.

* A scatter plot was created to visualize the relationship between sepal length and sepal width. Axes were labeled, and a title was provided for clarity. Experimentation with different colors and markers was conducted to enhance the visual appeal of the plot.

* Scikit-Learn was employed to train a logistic regression model on sepal length and width to predict iris species. The dataset was split into training and test sets using train_test_split. A logistic regression model was instantiated and fitted to the training data, and its performance was evaluated using the accuracy metric provided by the accuracy_score function.

Overall, through this exploration, we gained insights into the Iris dataset, performed various data analysis tasks, visualized the relationships within the data, and built a simple machine learning model for species classification. This process provided a comprehensive understanding of the dataset and demonstrated the capabilities of Python's data science libraries in handling and analyzing real-world datasets.
