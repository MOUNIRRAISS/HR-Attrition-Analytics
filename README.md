
 
# Welcome to the Portfolio of Raiss Mounir 🎓📊🚀 

### Table of contents
- [About Me 💼](#about-me)
- [Skills and Expertise 🚀](#skills-and-expertise)
- [What You'll Find Here 🌟](#what-youll-find-here)
- [Projects Showcase 🚀](#projects-showcase)
- [Project N°1 (HR Attrition Analysis)(Python & Power BI) ](#project-n1)
- [Project N°2](#project-n2)
- [Project N°3](#project-n3)
- [Project N°4](#project-n4)







  
  



### About Me 

#### Hello! I'm Raiss Mounir, a dedicated Data Analyst and Econometrician with a solid background in economics, data analytics, and applied research. I am passionate about transforming complex datasets into meaningful insights that empower informed decision-making. Holding a Master’s degree in Applied Econometrics, I excel at leveraging statistical tools and programming languages such as Python, R, SQL and Stata to uncover patterns, design predictive models, and solve real-world problems. Beyond technical expertise, I bring a collaborative mindset, meticulous attention to detail, and a strong commitment to delivering impactful results in every project.

###  Skills and Expertise 
- Data Cleaning, Analysis, and Visualization

- Econometric Modeling (Panel Data, Time Series)
 
- Statistical Programming (Python, R, SQL, Stata)

- Predictive Analytics 

- Dashboard Development (Power BI, excel)

###  What You'll Find Here 
This portfolio showcases my projects, skills, and achievements, including:

📊 Interactive dashboards for visualizing key trends and metrics.

📈 Advanced econometric models for real-world problem-solving.


### Projects Showcase 

Here are some of the key projects I’ve worked on, highlighting my skills in data analysis, econometrics, and visualization. Each project tackles a unique challenge and demonstrates my ability to transform data into actionable insights:
.














  
### Project N°1


**Title:**  HR Attrition Analysis 

**Description:**

This project focuses on analyzing employee attrition to help HR teams identify key drivers of employee turnover. Using an interactive dashboard, the project visualizes critical metrics such as attrition rates by department, age group, and job role, empowering decision-makers with actionable insights.

**Tools Used:** 

- Python for data cleaning and visualisation
- Power BI for dashboard creation.

**Data Source:**  
The data used for this project is sourced from the [Kaggle HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

### Python - Data Cleaning & Visualization 
**Step 1**: Importing Necessary Packages

The first step in any data analysis project is to import the necessary packages or libraries. These libraries provide the functions and tools needed to manipulate the data, perform computations, and create visualizations. Below is the code I used to import the required packages for this project:

![image](https://github.com/user-attachments/assets/2cb3f92b-eadf-43f4-8037-44612a090145)

 **Step 2**: Importing the Dataset 📊
 
The next step is to import the dataset into our Python environment. This is done using the pandas library, which allows us to easily load and manipulate data. Below is the code I used to import the dataset and display the first few rows for a quick preview.


![image](https://github.com/user-attachments/assets/8cfd8fd7-1ee6-438e-a270-f38f56699f98)

##### output 

![image](https://github.com/user-attachments/assets/353dd663-09c2-4164-be01-4b6aafe51560)

**Step 3**: Verifying the Dataset 🧐

After importing the dataset, it's important to verify its structure and understand the types of data it contains. We can do this using the info() function in pandas, which provides details about the dataset, such as the number of entries, column names, data types, and the presence of missing values.

![image](https://github.com/user-attachments/assets/b7709037-80c1-4d09-a208-b7440a32584a)

##### output 

![image](https://github.com/user-attachments/assets/6027d574-48d0-4e16-92cc-1abb4a55460c)

This output indicates that the dataset contains 1470 entries with no null values across all columns, which ensures data completeness. Additionally, the data types for each column are appropriate, with int64 for numerical variables and object for categorical variables. This suggests that the dataset is clean and ready for analysis, with no immediate need for data type corrections or null value handling.

**Step 4**: Checking for Duplicates 🔍

In data analysis, it's crucial to check for duplicate entries, as they can skew your results. To ensure the integrity of the dataset, we use the duplicated() function to identify any duplicate rows.


![image](https://github.com/user-attachments/assets/23660a78-47e6-409c-bec7-cb44a708de89)

##### output 

![image](https://github.com/user-attachments/assets/21fec74f-d845-4ce8-93df-b5cb775d70b8)

This output  confirms that there are no duplicate rows in the dataset. This indicates that the data is unique and does not require any deduplication process, ensuring the integrity of the dataset for analysis.


##### We have thoroughly verified the dataset, including checks for null values, duplicate rows, data types, unique identifiers, and potential inconsistencies. All aspects of the data are in good condition, with no issues requiring modification. The dataset is clean, complete, and ready for further analysis

**Step 5**: Descriptive Statistics 📊

To better understand the dataset, I performed descriptive statistical analysis using the describe() function in pandas. This step provides a summary of the dataset's numerical columns, helping to identify key metrics like the mean, median, and standard deviation.

![image](https://github.com/user-attachments/assets/dc46e0c3-dc35-4107-b7e7-cc044e8f3046)

##### output 

![image](https://github.com/user-attachments/assets/65a405d7-f4be-4bc5-a1f4-b5db88ae84c2)

Descriptive statistics provide a comprehensive overview of a dataset's key characteristics, allowing us to understand its structure and tendencies.

we have :

- Mean: The average value, indicating the central point.
- Standard Deviation: The variability around the mean.
- Range (Min and Max): The span from the smallest to the largest value.
- Q1 : The First Quartile The value below which 25% of the data falls.
- Q2 : The Second Quartile The middle value of the dataset when sorted. It divides the data into two equal halves.
- Q3 : The Third Quartile The value below which 75% of the data falls.

**Step 6** Attrition Analysis 

In this step, we analyze the Attrition column of the dataset to understand the distribution of employee attrition (whether employees left or stayed in the company).

![image](https://github.com/user-attachments/assets/fd15924a-eebb-46ad-be2e-2f2ca186698b)

##### output 

![image](https://github.com/user-attachments/assets/0ade1ee2-ba2c-47b3-86f9-9ddd7b3c92bc)

The Attrition Count indicates that out of the total 1470 employees in the dataset, 1233 employees stayed with the company (marked as 'No'), while 237 employees left the company (marked as 'Yes').

The Attrition Percentage reveals that approximately 83.88% of the employees stayed, while about 16.12% of employees left the company. This provides a clear picture of the employee retention rate, indicating that a relatively small proportion of employees decided to leave. However, it’s essential to explore the reasons behind the attrition. By analyzing various factors and variables (such as age, job satisfaction, work-life balance, etc.), we can identify the key drivers of employee turnover and gain valuable insights into areas that may need attention to reduce attrition

##### Here's a visualization

![image](https://github.com/user-attachments/assets/55d9c60f-1d57-4b45-9171-cb947589b59f)

**YES** means left
**NO** means stayed

**Step 7** Attrition Analysis by gender
In this step, we analyze the relationship between employee attrition and gender to determine if there are any gender-based patterns or differences in attrition rates.

![image](https://github.com/user-attachments/assets/21cab044-09d1-49da-ae61-f5940c4affa6)


##### output 

![image](https://github.com/user-attachments/assets/3e0263ce-8a07-405a-bf17-7996ad835111)







