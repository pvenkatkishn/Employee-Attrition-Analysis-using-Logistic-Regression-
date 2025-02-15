**<h1>Employee Attrition Analysis with Logistic Regression</h1>**   

<h3>Project Overview</h3>
The primary objective of this project is to help the Head of People Operations at McCurr Healthcare Consultancy to hire the best talent available and to retain them for as long as they can. For this purpose, two objectives are formulated:</br>
1. To identify the different factors that drive attrition</br>
2. To make a model to predict if an employee will attrite or not

<h3>Key Features</h3>

- Application of Logistic Regression to model employee attrition.
- Evaluation of model performance using metrics like accuracy, precision, recall, and F1 score.
- Interpretation of key predictors and their impact on attrition through odds ratios.
- Practical recommendations for reducing employee turnover based on data insights.

<h3>Tech Stack</h3>

Programming Language: Python

Libraries:
- **numpy** for numerical computations.
- **pandas** for data manipulation and cleaning.
- **matplotlib** and seaborn for data visualization.
- **sklearn** for logistic regression and performance evaluation.


<h3>Project Workflow</h3>

1. Reading a CSV file hosted on Google Drive into a pandas Dataframe
2. Dropping unwanted columns: Employee number, Over 18, Standard hours
3. Splitting the data into categorical & numerical variables
4. Numerical Variables:
   - Performing Exploratory Data Analysis and trying to understand the structure of the data
   - Finding a relationship between attrition & the other numerical variables
   - Realtionships between different numerical variables through a heat-map & histogram
5. Categorical Variables: 
   - Univariate, bi & multi-variate Analysis for categorical variables
   - Creating Dummy Variables
6. Model Building:
   - Scaling the data (Calculating Z-score using Standard scaling)
   - Stratified Sampling
   - Model Eval Criteria
7. Building the Logistic Regression Model
8. Identifying which factors +vely or -vely affect attrition rate (Understanding feature importance)
9. Precision Recall curve for Logistic regression for identifying threshold for optimal performance
10. Performance of the model using this threshold.

<h3>Results</h3>
✅ Employees working overtime are <ins>2.6 times more likely to leave</ins>.</br>
💡 <ins>Frequent business travel</ins> is associated with <ins>higher attrition rates</ins>.

<h3>Model Limitations:</h3> High overall accuracy but low recall for predicting actual attrition cases

<h3>Recommendations:</h3>
- Reduce overtime and balance workloads.</br>
- Reevaluate travel policies to improve employee satisfaction.
   
<h3>Future Enhancements:</h3>
- Explore additional features like employee engagement scores and manager feedback.</br>
- Apply advanced machine learning models (e.g., Random Forest or XGBoost) for better predictive accuracy.</br>
- Automate the end-to-end pipeline for real-time attrition monitoring.</br>

<h4>Visualizations depecting some of my key findings are shown below. Feel free to reach out if you have any other questions :)</h4>

1. Data Profiling
![p4](https://github.com/user-attachments/assets/a7664cbf-3f2f-48f1-903a-ce5c191e51b7)

2. Overtime, Employee Travel v Attrition Rate
![p3](https://github.com/user-attachments/assets/9786836f-7efc-40c2-8a3d-acc6e53647ec)

3. Heatmap depecting relationship b/w numerical variables 
![p2](https://github.com/user-attachments/assets/e6686f17-538f-41b3-9c7e-0fd4c8d43010)

4. Model performance depicted using a confusion matrix & heatmap
![p1](https://github.com/user-attachments/assets/72213cc2-ec34-47fb-9271-11394f2e3637)
