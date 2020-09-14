# ARules-emplyee-attrition
Implemented Apriori Association rules mining algorithm to analyze emplyee_attrition at a company
# Overview

to view the complete notebook with plotly graphs you can either copy the repositories github link and paste the url nbviewer.jupyter.org
or visit thie link:
https://nbviewer.jupyter.org/github/Ryanondocin2019/ARules-emplyee-attrition/blob/master/Employee%20Churn%20using%20Association%20Rules.ipynb

* This dataset provides a variety of information about employees, such as Age, Education, Hourly rate, Job Level, Marital status, Monthly income and lastly, whether or not they stay with the company( “Attrition” = 1: left the company, 'attrition' = 0: stay with the company)
* Utilized the Cross Industry Standard Process for Data Mining to derive analytical insights.
* Data preprocessing, cleaning, transformation was conducted to identify potential data quality issues.
* exploratory data analysis (EDA) was conducted so descriptive statistics could be shown and data patterns were illuminated using visualization tools such as matplotlib and plotly.
* Default ssociation rule mining algorithm was obtained for a baseline model.
* Following this, the model underwent extensive tuning by experimenting with different hyper-parameters.
* Finally the most significant rules which could predict “Attrition” were analyzed and discussed for those who stay vs. those who leave, respectively.
* Heroku was used to create a UI that could display the most significant association rules: Support vs Confidence (shaded by lift). It contains interactive sliders which represent tuneable hyperparameters and a bokeh plot of the aforemention graphical output. Please see
 attached movie file to investigate the results.
