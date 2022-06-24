# ANN-on-UCI-heart-disease-dataset

This is a small machine learning project that is performed on a heart disease dataset...
Libraries that we used consist of tensorflow, keras, pandas and etc.


Data Set Information:

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, 
the Cleveland database is the only one that has been used by ML researchers to this date. 
The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. 
Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).
The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

Only 14 attributes used:
1. #3 (age; in years)
2. #4 (sex; 1 = male; 0 = female)
3. #9 (cp; chest pain type) 
4. #10 (trestbps; resting blood pressure (in mm Hg on admission to the hospital))
5. #12 (chol; cholestoral in mg/dl)
6. #16 (fbs; fasting blood sugar > 120 mg/dl (1 = true; 0 = false))
7. #19 (restecg; resting electrocardiographic results)
8. #32 (thalach; maximum heart rate achieved)
9. #38 (exang; exercise induced angina (1 = yes; 0 = no))
10. #40 (oldpeak; ST depression induced by exercise relative to rest)
11. #41 (slope; the slope of the peak exercise ST segment)
12. #44 (ca; number of major vessels (0-3) colored by flourosopy)
13. #51 (thal; 3 = normal; 6 = fixed defect; 7 = reversable defect)
14. #58 (target) (the predicted attribute - 1 or 0)
