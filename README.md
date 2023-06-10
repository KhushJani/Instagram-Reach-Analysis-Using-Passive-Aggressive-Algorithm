# Instagram-Reach-Analysis-Using-Passive-Aggressive-Algorithm

This project focuses on analyzing Instagram reach using Python and various data analysis libraries. It includes data preprocessing, exploratory data analysis (EDA), visualization, and building a machine learning model for predicting reach.

### Dependencies

pandas: A library for data manipulation and analysis.
numpy: A library for mathematical operations on arrays.
matplotlib: A plotting library for creating visualizations.
seaborn: A statistical data visualization library based on matplotlib.
plotly: A library for interactive visualizations.
wordcloud: A library for generating word clouds.
scikit-learn: A machine learning library for data analysis and modeling.

### Data Preprocessing

The code reads data from a CSV file called "Instagram data.csv" using pandas. It then performs some data preprocessing steps to handle missing values by dropping rows with null values.

### Exploratory Data Analysis (EDA)

Several visualizations are created to explore the distribution of impressions from different sources such as home, hashtags, and explore. The code uses seaborn and matplotlib for creating histograms and seaborn for creating a pie chart to show the distribution of impressions from various sources.

Word clouds are generated to visualize the most common words in the captions and hashtags used in the Instagram posts.

Scatter plots are created to examine the relationships between likes, comments, shares, saves, profile visits, and follows with respect to impressions. The code uses plotly to create interactive scatter plots with trendlines.

### Correlation and Conversion Rate

The code calculates the correlation between different variables and impressions using the corr() function from pandas. It then prints the correlation values in descending order.

The conversion rate is calculated by dividing the total number of follows by the total number of profile visits and multiplying by 100.

### Machine Learning Model

A machine learning model called PassiveAggressiveRegressor is trained and evaluated using scikit-learn. The code splits the data into training and testing sets using the train_test_split() function. The model is trained on the training data and evaluated on the testing data using the score() function. Finally, a prediction is made using the trained model.
