<h1 align = "center">Employees_Turnover_Analysis_SalifortMotors</h1> 

<section>
<h2>Overview</h2> <p>The goal of this project was to build and evaluate a logistic regression model or the following machine learning models: decision tree, random forest, XGBoost to predict whether an employee will leave the company, and discover the reasons behind their departure. This project utilized ,HR_capstone_dataset.csv, self-reported information from employees of a multinational vehicle manufacturing corporation. The final random forest model performed with 96% accuracy and 87% precision determining what features were most important in employee retention. Based on the model, <b>last_evaluation, number_project, tenure, and overworked</b> are most important driving factor in employee departure.</p>
</section>

<section>
  <h2>Business Understanding</h2><p>Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees. It is important to understand what factors discoureage them to continue and fit in the company. </p>
</section>
<section>
  <h2>Data Understanding</h2><p>The HR_Capstone_Data.csv is the internal data accumulated and curated by the HR from the company employees.
.The data consisted of approximately 15k unique employee report records and 10 features. The features included information on satisfaction_level, last_evaluation, number_project, average_monthly_hours, time_spend_company, work_accident, left, promotion_last_5years, department, salary. The pie chart below shows the proportion of the departure status that exist in the data set.
</p>
  <img src="images/left and not left.png" alt="left vs not left ratio" width="300" align="center" />
<p>In connection to this, a feature was engineered to represent if the data used was leaked data/simulated data or actual data that that exactly replicate actual scenarios. Multiple redundant columns were dropped and reformatted into the proper data type. For example, satisfaction_level column was dropped and transformed into new attributes overworked.</p>
</section>

<section>
  <h2>Modeling and Evaluation</h2><p>A random forest model comprising 300 decision trees was used to determine feature importance in who are on verge of departure. The below plot shows that last_evaluation, num_project and the tenure of a employees were the Top 3 most important factors in determining a  probability of the employee daparture. The overall model performed with 96% accuracy and 87% precision. </p>
  <img src="images/rf feature importance.png" alt="Feature imporance chart of the random forest model" width="500" align ="center" />
</section>
<section><h2>Conclusion</h2><p>This model can benefit the executives of the company to plan and  built the effective data driven solution to prevent the employee leaving from the company and promote the good culture for employees and attract them for longer tenure. In the future, adding more information on a employees record and navigating historical data may also be beneficial in helping the stakeholder address their business problem. 
</p></section>

