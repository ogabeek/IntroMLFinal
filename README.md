# IntroMLFinal


Used Kaggale Dataset https://www.kaggle.com/datasets/lainguyn123/student-performance-factors/data
just in case also uploaded here "StudentPerformanceFactors.csv"

Main goal is get graded during the ML intro course 🙃
Minor Goal #2 is to identify which features makes the most impact on Student's performance from the df with shapes (6607, 20) and features such 





Used ML mode "RandomForestRegressor"

And the conclusion is 
RF Test RMSE: 2.154
RF Test R^2: 0.672

Top 10 feature importances:
                     feature  importance
1                 Attendance    0.378496
0              Hours_Studied    0.241777
3            Previous_Scores    0.086323
4          Tutoring_Sessions    0.035283
6       Parental_Involvement    0.034746
7        Access_to_Resources    0.032563
2                Sleep_Hours    0.028506
5          Physical_Activity    0.027441
9              Family_Income    0.017877
11  Parental_Education_Level    0.017488
The Random Forest’s performance dipped relative to linear regression (R²≈0.67 vs. 0.77), but it still gives us a clear ranking of which features drive predictions in a non‐linear setting. In this RF model:

Attendance (≈0.38 importance) and Hours_Studied (≈0.24) dominate—together they account for over 60% of the total importance.

Previous_Scores (≈0.086) and Tutoring_Sessions (≈0.035) follow next.

The next four are the mapped ordinal factors: Parental_Involvement (≈0.035), Access_to_Resources (≈0.033), Sleep_Hours (≈0.029), and Physical_Activity (≈0.027).

Finally, Family_Income (≈0.018) and Parental_Education_Level (≈0.017) round out the top ten.





Google Collab solution -> https://colab.research.google.com/drive/1Eznk6vKoy8wkkduFQbPmLH-CY2b2XnwF?usp=sharing
Also available as a .ipynb file above. 







