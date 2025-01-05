# Online-Gaming-Behavior-Project

This project was undertaken as part of my learning journey to explore the concepts of Data Science and Machine Learning. The objective was to analyze player behavior in online games and predict engagement levels based on specific features.

**Overview**

The dataset contains information about player behavior, such as session duration, frequency, and player level, which are critical factors influencing engagement. The primary goal was to:

1. Analyze player engagement patterns using exploratory data analysis (EDA).
2. Identify factors influencing engagement, such as session duration, player level, and gaming frequency.
3. Provide insights and recommendations to enhance player retention and gaming experience.
4. Build predictive models to classify players into engagement levels (Low, Medium, High).

**Exploratory Data Analysis (EDA)**

During EDA, I performed the following steps:

***Data Overview:***

1. Used pandas to load and clean the dataset.
2. Explored data types, checked for missing values, and summarized key statistics.

***Visualization:***

1. Plotted bar plots and box plots to understand the distribution of Categorical features and Numerical features across all Engagement Levels.
2. Used seaborn to plot heatmap to identify correlations between features, such as how session duration correlates with engagement level.

***Observations and Suggestions:***

Through EDA, I identified significant relationships between player behaviors and engagement levels. Based on these findings, I proposed general strategies to enhance player retention and engagement.

**Machine Learning Models**

To predict player engagement levels, I trained and evaluated the following four machine learning models:

***Logistic Regression:***

Why Used: A simple, interpretable linear model for classification.
Performance: Performance was acceptable.

***Linear Support Vector Classifier (Linear SVC):***

Why Used: Effective for high-dimensional data and linear decision boundaries.
Performance: Achieved good accuracy but required fine-tuning for optimal results.

***K-Nearest Neighbors (KNN):***

Why Used: A simple, instance-based method that makes predictions based on proximity.
Performance: Performed well but was sensitive to the choice of k and data scaling.

***Random Forest Classifier:***

Why Used: A robust ensemble method that combines multiple decision trees for better accuracy.
Performance: Delivered the best results with high accuracy and interpretability.

**Model Evaluation:**

Models were evaluated using accuracy, precision, recall, and F1-score.

**Best Model:** The Random Forest Classifier emerged as the most accurate and reliable predictor for engagement levels.

**Conclusion**

This project provided hands-on experience with the complete Data Science workflow, from data cleaning and visualization to machine learning model development. It helped me gain valuable insights into player engagement while building practical skills in data analysis, visualization, and predictive modeling.

Feel free to explore the code!
