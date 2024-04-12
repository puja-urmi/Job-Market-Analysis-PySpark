# Exploratory Analysis of Job Market Trends and Salary Prediction using PySpark
This project leverages PySpark to analyze job market data for uncovering insights and patterns. 

## Project Overview
A big dataset comprising over 1.6 million global records with 23 features spanning 25 months from September 2021 to September 2023 was collected from Kaggle. You can get the data here: https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

## 1. Data Engineering to Preprocess Data for EDA of Job Market using PySpark

**Methods**: In this part, I began by setting up the environment, installing PySpark, and ensuring Java compatibility. Next, I loaded the "job_descriptions.csv" dataset and meticulously preprocessed it, removing redundant features, addressing missing values, and organizing range data. Lastly, I saved the refined dataset for subsequent analysis, ensuring a thorough exploration of the dynamic job market landscape.

**Results**: A streamlined CSV file containing the essential data only with reduced size.

## 2. Descriptive Statistics to Exploring Job Market Trends using PySpark

**Methods**: In this segment, I have utilized PySpark's DataFrame capabilities to delve into trends within job postings. I have derived significant statistical insights related to salary, experience, company size, job title, qualifications, country, work type, portal, and preference. 

**Results**: After this statistical analysis, I found that the salary range for job postings fell between $55,000 and $65,000, with a median salary of $60,000. The maximum salary range extended from $80,000 to $130,000, with a median of $105,000. The dataset, containing approximately 1.6 million records, showed an average company size of 73,705 employees. Key job titles identified included UX/UI Designer, Digital Marketing Specialist, and Software Engineer, while top qualifications sought after were BBA, BA, and BCA degrees. Job postings were sourced from 216 countries, with varying frequencies across different work types and job portals. Notably, gender preferences in job postings were nearly evenly distributed among categories of "Male," "Female," and "Both.


## 3. Market Demand Analysis to Explore Trends using PySpark

**Methods**: Utilizing PySpark's robust capabilities, we extracted the most and least demanding skills from the dataset, shedding light on emerging trends in the job market. We then identified the most sought-after qualifications and job titles, providing insights into talent acquisition strategies and areas of declining relevance.

**Results**: The analysis of the top ten most demanding skills, job titles, and qualifications revealed key trends in the contemporary job market. There is a growing emphasis on digital proficiency and technical expertise, with skills like Google Analytics and Python, job titles like UX/UI Designer and Digital Marketing Specialist, and qualifications like BBA and BA dominating the landscape. Conversely, niche skills and specialized roles also hold relevance, indicating diverse opportunities within specific industries. Overall, these insights highlight the dynamic nature of skill demands, job roles, and educational qualifications, reflecting the evolving needs of industries and employers in today's digital age. 

<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/5f1c18a6-1266-4a1c-82bc-c0abb76f6b79">
<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/f31f0c91-2f39-489a-be38-69a620685b69">
<img width="220" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/07f76853-5e3d-47ce-8176-ce7322cf856d">
<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/e1c8b520-7309-4bab-90d6-2781d8957ef2">


## 4. Temporal Analysis to Explore Temporal Trends in Job Market using PySpark

**Methods**: Yearly, monthly, weekly, and daily analyses were conducted to examine trends, variations, and fluctuations in job postings. These analyses provide insights into long-term patterns, seasonal trends, and immediate responses to external factors, guiding recruitment strategies and optimization efforts.

**Results**: It revealed dynamic fluctuations in job postings across different years, with 2022 showing the highest activity, followed by 2023, and a comparatively lower count in 2021 surely because of partial data. Monthly trends suggest consistent activity with occasional declines in February and September, potentially influenced by seasonal or industry-specific factors. Weekly analysis highlights spikes and dips in recruitment activity, indicating periods of increased or decreased hiring. The daily histogram shows a consistent pattern, with the most prevalent job postings per day clustered around the 2200 mark. Overall, these findings provide valuable insights into the evolving dynamics of job market activity, influenced by various external factors. 

<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/b35ad444-191e-4e18-8e76-354d8faeccff">
<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/5605fd7a-8740-4bd5-a2cb-c7c5ad2ab5d7">
<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/c4f3c5dc-7036-4e5b-96be-e3167cce51dc">
<img width="200" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/5d817c23-dfcb-4504-ae91-3feb5bacdc8a">


## 4. Salary Analysis to Explore Salary Trends in Job Market using PySpark

**Methods**: PySpark was employed to compute and visualize average salary levels across job roles, industries, and countries, revealing disparities and providing insights into regional and sectoral differences.

**Results**:The analysis revealed diverse salary distributions across job titles, with some roles commanding notably higher average salaries, such as Financial Controller and IT Administrator, indicating their demand and significance in the job market. Conversely, roles like IT Manager and HR Generalist show lower average salaries, suggesting potential challenges in compensation competitiveness. Top-paying companies like Playtech and Leidos Holdings prioritize offering competitive compensation packages, while companies like DISH Network and Bosch Group demonstrate a trend towards lower average salaries. Globally, countries like Bosnia and Herzegovina and South Sudan exhibit higher average salaries, highlighting economic disparities and the complex interplay of socioeconomic factors driving wage trends.

<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/f0349138-02d5-4666-afa2-070d688c2c27">
<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/97c2445f-4802-40e0-8b8b-e848a7e3fa64">
<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/637593e8-bb50-4c35-bfb9-e74e331dbd88">
<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/5cb23f54-3d83-4958-839f-01153466344a">
<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/900f7106-c392-4dde-996e-901c89982593">
<img width="412" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/c77d74ad-f6d1-41cb-abcc-41cceb6aebae">


## 6. Correlation Analysis to Explore Correlations Between Features using PySpark

**Methods**: The methodology involves converting data types and encoding to ensure numerical compatibility, followed by correlation analysis to assess feature relevance to salary ranges. Less important features identified through correlation are then removed to refine the dataset for enhanced salary prediction accuracy, and the processed data is saved for subsequent model training.

**Results**: Upon analyzing the dataset, it becomes apparent that every feature exhibits some level of correlation with our target variables maximum and minimum salaries. However, the nature of these correlations differs significantly between maximum and minimum salaries. Minimum salary shows strong correlations with job title and location, whereas maximum salary is more closely correlated with responsibilities and skills. Although minimum salary demonstrates correlations with nearly all features, maximum salary displays negligible correlations with most features, except for a few select ones. This distinction is logical, as minimum salary tends to be influenced by factors like geographical location and job type, whereas maximum salary is predominantly determined by the level of responsibilities and skills associated with the position. Since no feature exhibits zero correlation with both target variables, I've opted not to remove any features based solely on their lack of correlation with the target variable.

<img width="410" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/695e4ca1-0313-4370-b9ab-0ae039f1a65a">
<img width="415" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/21e8d442-f3ea-40ef-a59a-951ad3933d17">


## 7. Modeling and Salary Prediction using PySpark

**still working on it**

## 8. Modeling and Salary Prediction using Scikit-learn

**Methods**: The methodology involves initial data preprocessing steps, including one-hot encoding, feature scaling, and a split into 80:20 for training and testing datasets. Subsequently, various models, ranging from linear regression to XGBoost, are trained and evaluated using 5-fold cross-validation and grid search for hyperparameter tuning. Performance evaluation metrics such as Mean Squared Error and R2 score are employed to assess model performance on the testing set, with visualization facilitated by Matplotlib.

**Results**: After rigorous evaluation using 5-fold cross-validation and grid search, tree-based models emerged as the top performers for salary prediction, with decision trees leading the pack. Random forests and XGBoost followed closely behind.

<img width="825" alt="image" src="https://github.com/puja-urmi/Job-Insights-in-PySpark/assets/150852458/0857eea0-e4c4-411a-90bd-ba11aab5ee69">


PS: In this project, I've learned that scikit-learn isn't suitable for big data modeling; PySpark is essential here for its scalability but compatibility issues may arise in non-macOS environments, necessitating Hadoop framework installation.





