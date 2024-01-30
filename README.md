Classification Analysis - Heart Disease Patients

The importance of identifying heart disease in patients early cannot be overstated.
As such, this project aims to assess the efficacy of predicting a patient's likelihood of having heart disease based on two key factors:

ST depression (Note: ST corresponds to a segment seen in an ECG test. If the segment appears abnormally low and sits below the baseline, the person is said to have ST depression)
maximum heart rate
to answer the question:
How accurately can the presence of heart disease be predicted in patients through the classification of ST depression induced by exercise relative to rest and maximum heart rate as key factors in the assessment?

As a part of EDA, we created a separate scatterplot for each possible pairs of numeric variables, and in comparing each of these plots with each other, we saw that the presence of heart disease seems to be correlated to a low ST depression and a high maximum heart rate, which led us to choose these two variables for our analysis. Classification was used for our algorithm because we want to predict the categorical class label (healthy or presence of heart disease) based on our variables. If we had more time and resources we would also have liked to explore other risk factors, such as patients' sex and age, but we chose to concentrate on a select set of variables to keep the project more manageable.
