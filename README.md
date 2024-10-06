# Machine-Learning-Coursework

Working Conditions Research
Analyzed variables using Machine Learning Framework

Adopted techniques such as: K-Means Clustering, Math Regression Model, Forward/Backward Selection, K-Fold Cross Validation and Data Visualization

Main programming Language used: R

For easier viewing of this research, here are the screenshots:

<img width="678" alt="image" src="https://github.com/user-attachments/assets/15f7e609-cad2-4fa0-8011-9284a4870615">

<img width="495" alt="image" src="https://github.com/user-attachments/assets/75feabb8-98ba-433b-a5d4-dada64f8e51f">

<img width="544" alt="image" src="https://github.com/user-attachments/assets/5f2327be-9976-410f-a903-b583c04d8b6b">

<img width="494" alt="image" src="https://github.com/user-attachments/assets/dccf8619-e242-4970-a16b-217fa2eba4ee">

<img width="485" alt="image" src="https://github.com/user-attachments/assets/bdaa31ca-626e-44e9-9539-50f51dc5a7b3">

<img width="475" alt="image" src="https://github.com/user-attachments/assets/9bc99c63-b837-428c-8a2d-c4cef4ca4840">

<img width="503" alt="image" src="https://github.com/user-attachments/assets/97498507-1a1e-4ce2-99d6-7e38444734b3">

<img width="643" alt="image" src="https://github.com/user-attachments/assets/c633c651-efd3-4472-9a03-660875debea0">

<img width="564" alt="image" src="https://github.com/user-attachments/assets/80816087-b1b9-44b6-8e6a-7df35921eb56">

<img width="518" alt="image" src="https://github.com/user-attachments/assets/42ec4e72-1642-4d28-9047-e046c10dc0f5">

<img width="474" alt="image" src="https://github.com/user-attachments/assets/56375400-d7a3-43b2-a4f0-844e5463a524">

Summary

Part 1: Data Analysis of European Working Conditions Survey (EWCS)

Correlation Analysis:
Figures show that Age and Gender (Q2a and Q2b) have little correlation with the perceptions of working conditions (Q87a to Q90f).

Response Patterns:
Most respondents indicated "most of the time" for most questions, while Q90f showed a strong confidence in job performance, reflected by the "always" response.

Principal Component Analysis (PCA):
PC1 and PC2 together explain 52.85% of the variance in the data.
Variables Q87 and Q90a are closely linked to PC1, while other Q90 variables relate more to PC2.

K-Means Clustering:
The optimal number of clusters is two. Both clusters show similar age and gender distributions, but Cluster 2 has a more positive outlook on working conditions.

Part 2: Academic Performance Analysis

Correlation in Math and Portuguese Datasets:
Little correlation found among most variables, except for parents' education and alcohol consumption patterns.

Regression Models:

Math:

Backward selection provided the best model (adjusted R² = 0.301), identifying key factors affecting scores, such as Father's Job, Failures, and Absences.

Portuguese:

Backward selection again yielded the best model (adjusted R² = 0.3629), highlighting significant variables like Age, Study Time, and School Supplementary.

Part 3: Bank Client Data Analysis

Demographics:

The highest client demographic is aged 31-45.

Regression Model:

The outcome of the previous marketing campaign is the most significant predictor for current campaign outcomes (odds ratio = 10.37).
The model achieved an accuracy of 90.02%.

Model Evaluation:

The Receiver Operating Characteristic (ROC) curve indicates strong predictive accuracy.
Random Forest analysis identified "duration" as the most significant factor influencing campaign outcomes.

Conclusion

Overall, the research employed various statistical methods to analyze data from multiple surveys, revealing significant insights into working conditions, academic performance, and client demographics in a banking context. The backward selection method consistently provided the best predictive models in the academic performance analyses, while demographic insights and marketing campaign outcomes were emphasized in the banking analysis.
