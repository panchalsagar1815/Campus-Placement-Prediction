
# **Project Title: Campus Placement Prediction**

**Overview:**
The "Campus Placement Prediction" project aims to build a predictive model that forecasts the placement status and salary of students based on various features such as academic performance, gender, work experience, and more. By leveraging data cleaning, preprocessing, and a sophisticated model, this project provides valuable insights for students, universities, and recruiters in anticipating placement outcomes.

**Key Features:**

1. **Data Collection and Cleaning:**
   - Compiled a comprehensive dataset including features like sl_no, gender, ssc_p, ssc_b, hsc_p, hsc_b, hsc_s, degree_p, degree_t, workex, etest_p, specialisation, mba_p, status, and salary.
   - Applied data cleaning techniques to handle missing values, and outliers, and ensure data integrity.
   - Ensured consistency and accuracy in the dataset to enhance the reliability of predictions.

2. **Data Visualization:**
   - Utilized data visualization techniques to explore the distribution and relationships between different features.
   - Generated insightful visualizations, such as histograms, scatter plots, and correlation matrices, to understand the impact of each variable on placement status and salary.

3. **Input Pipeline and Preprocessing:**
   - Created an efficient input pipeline to handle the loading and preprocessing of data.
   - Performed feature scaling, normalization, and encoding categorical variables to prepare the data for model training.
   - Ensured that the data was well-structured and ready for input into the predictive model.

4. **Model: LGBMRegressor**
   - Developed a predictive model using the LGBMRegressor algorithm, configured with specific parameters for optimal performance.
   - Leveraged LightGBM's ability to handle large datasets efficiently and provide accurate predictions.
   - Trained the model on the preprocessed dataset, allowing it to learn patterns and relationships between features and placement outcomes.

5. **Prediction Metrics:**
   - Evaluated the model's performance using relevant metrics for both binary classification (placement status) and regression (salary prediction).
   - Assessed metrics such as accuracy, precision, recall for placement status, and mean squared error (MSE) for salary prediction.

**Conclusion:**
The "Campus Placement Prediction" project provides a valuable tool for universities and students to gauge potential placement outcomes. The LGBMRegressor model, with its efficient handling of large datasets, demonstrates the capability to predict both placement status and expected salaries accurately. This project contributes to streamlining the placement process and helping stakeholders make informed decisions based on historical data and trends. Future work may involve continuous model refinement, incorporating more features, and expanding the dataset for increased predictive accuracy.
