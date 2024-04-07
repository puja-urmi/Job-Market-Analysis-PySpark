# Exploratory Analysis of Job Market Trends and Salary Prediction using PySpark
This project embarks on an in-depth exploration of job market data utilizing PySpark, a powerful tool known for its scalability and efficiency in handling vast datasets. The primary goal is to unveil hidden insights and discernible patterns within the dynamic job market landscape.

Data:  A big dataset comprising over 1.6 million global records with 23 features spanning 25 months from September 2021 to September 2023 was collected from Kaggle. You can get the data here: https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

## Project Overview
PS: I have structured this project into multiple notebooks, each dedicated to a specific task, starting from data engineering and arranged in a sequential manner. The names of the notebooks correspond to the sections mentioned below. This project was developed using the PySpark's Python library, in a macOS, which required installation of java environment. It's important to acknowledge that there might be compatibility issues in Linux and Windows environments, which could require the installation of the Hadoop framework.

## 1. Data Engineering
Title: Data Engineering to Preprocess Data for EDA of Job Market

### Notebook Breakdown: 
- Installing and Importing Required Resources: All necessary resources, including PySpark, will be installed and imported to facilitate the project's subsequent stages. Othern than these you will need to install Java in your system to run this. 
- Loading Data: The CSV data file "job_descriptions.csv" will be loaded to initiate data exploration and preprocessing using PySpark functionalities.
- Removing Unnecessary Features: Only the most valuable features for analysis will be retained, while less significant columns will be discarded.
- Handling Missing Values: Various techniques will be employed to effectively address missing values, ensuring minimal impact on analysis outcomes.
- Splitting Range Data: Ranges such as salary or experience ranges will be segregated into separate columns to facilitate analysis.
- Eliminating Duplicate Features: Duplicate entries and extraneous features will be identified and removed to enhance dataset quality. Any blank entries will be identified and handled appropriately.
- Data Type Conversion: Ensuring accurate data types for each feature is crucial for conducting precise analysis.
- Saving the Processed Data: After completing all preprocessing steps, the new DataFrame will be saved as a CSV file for further analysis in subsequent notebooks.

By meticulously executing these preprocessing steps, the dataset will be prepared for in-depth analysis, ensuring robustness and reliability in uncovering actionable insights into the dynamic job market landscape.


## 2. Descriptive Statistics
Title: Exploring Job Market Trends with Descriptive Statistics in PySpark

### Notebook Breakdown: 
- Importing Required Resources: We begin by importing all necessary resources to support our analysis. Assuming resource installation has been completed in a preceding data processing notebook, we proceed directly to import them here.
- Data Loading and Visualization: Next, we load the processed data from "processed_job_descriptions.csv" using PySpark. Through PySpark DataFrame operations, we conduct an initial data exploration.
- Descriptive Statistics: Within this section, we harness PySpark's DataFrame functionalities to explore trends in job postings by Key statistical insights were derived concerning salary, experience, company size, job title, qualifications, country, work type, portal, and preference.
Through this PySpark exploration, our objective is to furnish stakeholders with actionable insights and a comprehensive understanding of essential features for navigating the intricacies of the modern job market. Following this analysis, we anticipate gaining deeper insights into these features and the entire dataset.


## 3. Market Demand Analysis
Title: Exploring Skill, Jobs, and Qualifications Demands in Market using PySpark

### Notebook Breakdown: 
- Importing Required Resources , Data Loading and Visualization are similar to previous notebooks
- Most Demanding Skills: Leveraging PySpark's robust capabilities, the most in-demand skills are extracted from the dataset. This analysis provides insights into the skills sought after by employers, shedding light on emerging trends and preferences in the job market.
- Least Demanding Skills: Conversely, the least demanded skills are identified to discern patterns of declining relevance or niche skill requirements in the market.
- Most Demanding Qualifications: The qualifications most frequently requested by employers are examined, highlighting educational backgrounds and credentials preferred in the current job landscape.
- Most Demanding Jobs: PySpark is utilized to identify the most sought-after jobs in the market. This analysis offers insights into the types of roles experiencing high demand in current market and provides context for talent acquisition strategies.
- Least Demanding Jobs: Similarly, the least demanded job titles are explored to understand roles with lower demand or declining relevance in the job market.


## 4. Temporal Analysis
Title: Exploring Temporal Trends in Job Market using PySpark

## Notebook Breakdown
- Importing Required Resources , Data Loading and Visualization are similar to previous notebooks
- Yearly Analysis: For the yearly analysis, trends in job postings aggregated annually are examined. Year-over-year changes are analyzed to identify overarching patterns and shifts in job market activity, providing insights into long-term trends.
- Monthly Analysis: In the monthly analysis, variations in job postings month by month are explored. Seasonal patterns, peak hiring periods, and potential fluctuations influenced by economic conditions and industry trends are uncovered, offering a granular view of job market dynamics.
- Weekly Analysis: The weekly analysis dissects job postings on a weekly basis to identify short-term fluctuations, spikes, and dips in job market activity. Weekly hiring patterns and responses to specific events or campaigns are scrutinized to optimize recruitment efforts.
- Daily Analysis: Daily fluctuations in job postings are scrutinized to identify immediate changes in job market dynamics and responses to external stimuli. The impact of short-term events on job market activity is assessed to adapt recruitment strategies and capitalize on emerging opportunities.



- Salary Analysis: Salary distributions across job roles and industries are comprehensively analyzed using PySpark's statistical functions. Histograms and box plots visually depict prevailing compensation trends, informing stakeholders with actionable insights.

- Modeling and Salary Predictions: Machine learning models are utilized for salary prediction based on data features, providing valuable predictive insights.

- Documentation: Key findings and insights are comprehensively documented using Markdown cells within PySpark notebooks, offering stakeholders actionable recommendations to navigate the dynamic job market landscape effectively.

Through this exploration using PySpark, the project aims to equip stakeholders with actionable insights and a comprehensive understanding essential for navigating the complex dynamics of the modern job market landscape.





