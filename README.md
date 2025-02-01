<h1 align = "center">Employees_Turnover_Analysis_SalifortMotors</h1> 

<section>
<h2>Overview</h2> <p>The goal of this project was to build and evaluate a logistic regression model or the following machine learning models: decision tree, random forest, XGBoost to predict whether an employee will leave the company, and discover the reasons behind their departure. This project utilized ,HR_capstone_dataset.csv, self-reported information from employees of a multinational vehicle manufacturing corporation. The final random forest model performed with 96% accuracy and 87% precision determining what features were most important in employee retention. Based on the model, <b>last_evaluation, number_project, tenure, and overworked</b> are most important driving factor in employee departure.</p>
</section>

<section>
  <h2>Business Understanding</h2><p>Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees. It is important to understand what factors discoureage them to continue and fit in the company. </p>
</section>
<section>
  <h2>Data Understanding</h2><p>The HR_Capstone_Data.csv is the internal data accumulated and curated by the HR from the company employees.
.The data consisted of approximately 15k unique employee report records and 10 features. The features included information on satisfaction_level, last_evaluation, number_project, average_monthly_hours, time_spend_company, work_accident, left, promotion_last_5years, department, salary. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set.
</p>
  <img src="images/Fig1.png" alt="Generous VS Non-Generous tippers" width="600" />
<p>In connection to this, a feature was engineered to represent if a ride was taken during rush hour or not. Multiple redundant columns were dropped and reformatted into the proper data type. </p>
</section>

<section>
  <h2>Modeling and Evaluation</h2><p>A random forest model comprising 100 decision trees was used to determine feature importance in who would tip generously or not. The below plot shows that trip duration, distance, and the cost of a fare were the Top 3 most important factors in determining a generous tipper from a non-generous one. The overall model performed with 86% accuracy and 72% precision. </p>
  <img src="images/Fig2.png" alt="Generous VS Non-Generous tippers" width="600" />
</section>
<section><h2>Conclusion</h2><p>This model can benefit Taxi Drivers in knowing if they will be tipped generously or not; however, running a parametric model to determine how much each variable will influence the actual price of the tip. In the future, adding more information on a rider’s past tipping behavior may also be beneficial in helping the stakeholder address their business problem. 
</p></section>

