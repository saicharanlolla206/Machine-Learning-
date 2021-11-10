# Machine-Learning-
Created a machine learning project for KIET Hackathon

PROBLEM STATEMENT:
Here we are going to take the previous employes dataset and analyze the probability of employes left the company and reasons why they left the company.
so this will be helpfull inorder to reduce the employes leaving the company.

PROCESS:
1)Imported dataset by using pandas library.
2)performed exploratory data analysis(EDA) on the employee dataset:
  a.Handling missing variables
  b.Numerical variables 
  c.categorial features
  d.Visualized dataset using matplotlib and seaborn
3)model building using XGBRFClassifier algorithm.

outcome:
EDA:
-In terms of education employees with Masters degree are most likely to leave the company.
-Employees who joined in recent year are most likely to leave the company. Maybe they are not satisfied with thier salary or their department work culture.
-Employee from Pune are most likely to leave the company.
-In terms of Salary , employee with PaymentTier 2 are most likely to leave the company.
-Female employee are more likely to leave the company.
-Most of the employee who were benched left the company.
-As we analysed in joining year the employees with less experience are the one's who are leaving the company.

CONCLUSION:
By using XGBRFClassifier algorithm we got 87.54027926960258 % accuracy.

Team members:
1)L.sai charan</br >
2)V.S.V.Tarun
3)G.S.S.Sai Kiran
4)P.Suneetha
5)K.Sireesha
