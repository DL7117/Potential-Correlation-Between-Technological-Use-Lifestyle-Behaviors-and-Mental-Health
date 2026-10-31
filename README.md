**Screen Time and Mental Wellness**

**Project Overview**

This project explores the relationship between technology use and mental well-being, with particular attention to screen time, sleep habits, and other lifestyle factors.

I was interested in understanding how everyday technology use might be associated with different aspects of our lives. To investigate this, I worked with a dataset containing information about screen time, sleep duration, sleep quality, physical activity, social interaction, and mental wellness.

Using Python, I performed exploratory data analysis, statistical analysis, data visualization, and machine learning. The project also provided an opportunity to apply concepts I had been learning in programming, statistics, and data science to a topic that connects with my interest in psychology.

**Objectives**

The main objectives of this project were to:

* Examine the relationship between screen time and mental wellness.
* Investigate how screen time relates to sleep duration.
* Explore the relationships between lifestyle factors and mental wellness.
* Develop and compare machine learning models for predicting mental wellness scores.
* Evaluate the results and consider the limitations of the analysis.

**Methodology**

The project followed several stages of the data science workflow.

**1. Data Exploration and Cleaning**

Examined the dataset, reviewed its variables, and prepared the data for analysis. This included investigating the distributions of individual variables and identifying patterns that could be explored further.

**2. Exploratory Data Analysis and Visualization**

Used statistical summaries and visualizations to examine relationships among screen time, sleep habits, physical activity, social interaction, and mental wellness.

**3. Statistical Analysis**

Applied linear regression to investigate the relationships between selected variables. In particular, I examined the associations between screen time and mental wellness, as well as between screen time and sleep duration.

**4. Machine Learning**

Developed and compared Linear Regression and Random Forest models to predict mental wellness scores. I also experimented with different combinations of input features to examine their influence on predictive performance.

**5. Model Evaluation**

Evaluated model performance using R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE). I also used cross-validation to examine how consistently the models performed across different data splits.

**Results and Findings**

The statistical analysis revealed a negative association between screen time and mental wellness scores. A simple linear regression model produced an R² value of approximately 0.404, suggesting that screen time accounted for a portion of the variation in mental wellness scores within the dataset.

I also examined the relationship between screen time and sleep duration. This relationship was considerably weaker, with an R² value of approximately 0.110.

For the prediction task, I compared Linear Regression and Random Forest models. Their test-set R² scores were approximately 0.758 and 0.745, respectively. Further cross-validation showed that the best-performing Random Forest configuration achieved an average R² of approximately 0.679, with an MAE of 9.02 and an RMSE of 11.77.

These comparisons demonstrated that a more complex model does not necessarily produce better predictive results. Model selection requires consideration of both predictive performance and consistency across different data samples.

It is important to note that the findings describe associations and predictive patterns within the dataset. They do not establish causal relationships between screen time, sleep, and mental wellness.

**What I Learned**

This project expanded my understanding of how programming can be used beyond developing software. Through data analysis, I learned how to use code to investigate questions, identify patterns, and evaluate possible relationships between variables.

I also gained practical experience with several aspects of the data science workflow, from preparing and exploring data to training and evaluating machine learning models. More importantly, I learned that interpreting results requires more than simply producing visualizations or obtaining a high model score. Understanding the data and recognizing the limitations of an analysis are equally important.

I hope to continue developing my skills in data analysis and machine learning, particularly in areas where data science can contribute to a better understanding of human behavior and psychology.

**Limitations and Future Improvements**

This project has several limitations. The findings are dependent on the dataset used and may not generalize to other populations or circumstances. Furthermore, the predictive models identify patterns in the available data but cannot establish causal relationships.

**Future improvements could include:**

* Testing the analysis on additional real-world datasets.
* Exploring feature importance and the individual contributions of different variables.
* Experimenting with additional machine learning algorithms and evaluation techniques.
* Investigating more closely the relationships between technology use, sleep, and other aspects of mental well-being.

**Tools and Technologies**

* Python — Primary programming language
* pandas — Data manipulation and analysis
* NumPy — Numerical operations
* Matplotlib — Data visualization
* scikit-learn — Statistical modeling, machine learning, and model evaluation
