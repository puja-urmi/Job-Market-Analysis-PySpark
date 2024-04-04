# Exploratory Analysis of Job Market Trends and Salary Prediction using PySpark
This project embarks on an in-depth exploration of job market data utilizing PySpark, a powerful tool known for its scalability and efficiency in handling vast datasets. The primary goal is to unveil hidden insights and discernible patterns within the dynamic job market landscape.

Data:  A big dataset comprising over 1.6 million global records with 23 features spanning 25 months from September 2021 to September 2023 was collected from Kaggle. You can get the data here: https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

## Project Overview
PS: I have structured this project into multiple notebooks, each dedicated to a specific task, starting from data engineering and arranged in a sequential manner. The names of the notebooks correspond to the sections mentioned below. This project was developed using the PySpark's Python library, in a macOS, which required installation of java environment. It's important to acknowledge that there might be compatibility issues in Linux and Windows environments, which could require the installation of the Hadoop framework.

1. Data Engineering: 
Title: Data Engineering to Preprocess Data for EDA of Job Market

Notebook Breakdown: 
- Installing and Importing Required Resources: All necessary resources, including PySpark, will be installed and imported to facilitate the project's subsequent stages. Othern than these you will need to install Java in your system to run this. 
- Loading Data: The CSV data file will be loaded to initiate data exploration and preprocessing using PySpark functionalities.
- Removing Unnecessary Features: Only the most valuable features for analysis will be retained, while less significant columns will be discarded.
- Handling Missing Values: Various techniques will be employed to effectively address missing values, ensuring minimal impact on analysis outcomes.
- Splitting Range Data: Ranges such as salary or experience ranges will be segregated into separate columns to facilitate analysis.
- Eliminating Duplicate Features: Duplicate entries and extraneous features will be identified and removed to enhance dataset quality. Any blank entries will be identified and handled appropriately.
- Data Type Conversion: Ensuring accurate data types for each feature is crucial for conducting precise analysis.
- Saving the Processed Data: After completing all preprocessing steps, the new DataFrame will be saved as a CSV file for further analysis in subsequent notebooks.

By meticulously executing these preprocessing steps, the dataset will be prepared for in-depth analysis, ensuring robustness and reliability in uncovering actionable insights into the dynamic job market landscape.


2. Descriptive Statistics:
   Leveraging PySpark's DataFrame operations, descriptive statistics are computed to understand the distribution of key variables such as job titles, salaries, and geographical locations, providing a solid foundation for further analysis.

- Exploring Job Market Trends: Trends in job postings are meticulously examined by aggregating data on job types, degree types, work types, and preferences. Visual representations such as bar plots reveal significant trends and fluctuations within the job market landscape.

- Temporal Analysis: PySpark's time-series functionalities are utilized to dissect trends over time. Job postings are aggregated into discrete intervals, enabling the identification and visualization of significant temporal trends using line charts and bar plots.

- Emerging Trends: PySpark facilitates the identification of latent patterns through rigorous frequency analysis. Emerging trends are identified and elucidated using PySpark MLlib and Spark NLP, providing valuable insights into evolving job market dynamics.

- Geospatial Analysis: Geographical patterns and regional disparities within the job market landscape are elucidated through advanced geospatial analysis. PySpark's capabilities are leveraged to spatially map job postings, identifying clusters and hotspots. Spatial join operations link job postings with geographical regions, enabling comprehensive visualization through cartographic representations.

- Skill Demand Analysis: Text processing functionalities are employed to analyze skills and qualifications extracted from job descriptions. Frequency analysis and text mining techniques identify sought-after skills and keywords, offering insights into prevailing skill trends.

- Industry and Sector Analysis: Segmenting job market data based on industry and sector categorizations provides insights into sector-specific dynamics. Growth rates and demand metrics are computed, facilitating visualization and analysis across distinct industry sectors.

- Salary Analysis: Salary distributions across job roles and industries are comprehensively analyzed using PySpark's statistical functions. Histograms and box plots visually depict prevailing compensation trends, informing stakeholders with actionable insights.

- Modeling and Salary Predictions: Machine learning models are utilized for salary prediction based on data features, providing valuable predictive insights.

- Documentation: Key findings and insights are comprehensively documented using Markdown cells within PySpark notebooks, offering stakeholders actionable recommendations to navigate the dynamic job market landscape effectively.

Through this exploration using PySpark, the project aims to equip stakeholders with actionable insights and a comprehensive understanding essential for navigating the complex dynamics of the modern job market landscape.





