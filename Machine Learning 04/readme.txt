Problem Statement

Predict a job’s average salary (USD) from its attributes (skills, experience, industry, company size, etc.).




Key Insights from EDA:

1. Salary distribution is fairly uniform with a slight concentration between $90k–$150k.

2. Experience level does not show a strong impact on salary, suggesting the dataset may be synthetic or lacks real-world progression.

3. Industry-wise salary differences are minimal, indicating weak variation across sectors.

4. Company size does not significantly influence salary levels.

5. Skills such as TensorFlow, Pandas, and SQL appear most frequently, indicating demand for data and ML-related tools.

6. Strong correlation exists between min, max, and average salary as expected.




From ML models:

This project focuses on predicting salary trends in the job market using a structured machine learning pipeline. After performing exploratory 
data analysis, I identified that most features were categorical or text-based, so I applied one-hot encoding for categorical variables and 
TF-IDF vectorization for the skills column. I engineered the target variable by converting salary ranges into a numerical average salary, 
which made it suitable for regression modeling. Using a pipeline ensured proper preprocessing, avoided data leakage, and made the workflow 
reproducible. I trained a Random Forest model and evaluated its performance, and then used feature importance to interpret the model. 
The results showed that experience level, specific technical skills, and job role are the most influential factors in determining salary. 
Overall, the project demonstrates not just prediction capability, but also provides meaningful insights into what drives salary variations in 
the AI-driven job market.

