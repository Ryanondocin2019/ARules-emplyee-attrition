# ARules-emplyee-attrition
Implemented Apriori Association rules mining algorithm to analyze emplyee_attrition at a company
# Overview
* This dataset provides a variety of information about employees, such as Age, Education, Hourly rate, Job Level, Marital status, Monthly income and lastly, whether or not they stay with the company( “Attrition” = 1: left the company, 'attrition' = 0: stay with the company)
* Utilized the Cross Industry Standard Process for Data Mining to derive analytical insights.
* Data preprocessing, cleaning, transformation was conducted to identify potential data quality issues.
* exploratory data analysis (EDA) was conducted so descriptive statistics could be shown and data patterns were illuminated using visualization tools such as matplotlib and plotly.
* Default ssociation rule mining algorithm was obtained for a baseline model.
* Following this, the model underwent extensive tuning by experimenting with different hyper-parameters.
* Finally the most significant rules which could predict “Attrition” were analyzed and discussed for those who stay vs. those who leave, respectively.
* Heroku was used to create a UI that could display the results of the algorithm. It included sliders which represented tuneable hyperparameters and a bokeh plot graphed models output (association rules). Please see the attached movie file to investigate the results.

