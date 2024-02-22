# dataviz_ass1
This is the first assignment for the data visualization lecture

With your dataset comprising variables like Glucose level, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, and Outcome, you have a rich set of data points to explore for insights into diabetes. Let’s briefly explain each variable and suggest appropriate visualizations to uncover patterns or relationships that may exist within the data.

1. Glucose Level
Explanation: This represents the plasma glucose concentration a few hours after eating. It's a crucial indicator for diagnosing diabetes, with higher levels potentially indicating diabetes or prediabetes.
Visualization: Histograms to show the distribution of glucose levels; Box plots by Outcome (0 = no diabetes, 1 = diabetes) to compare glucose levels in diabetic vs. non-diabetic individuals.

3. Blood Pressure
Explanation: The pressure of the blood in the circulatory system. Consistently high blood pressure (hypertension) is common in individuals with diabetes and can lead to further health complications.
Visualization: Scatter plots to explore the relationship between blood pressure and glucose levels; Box plots to compare blood pressure across outcomes.

5. Skin Thickness
Explanation: Triceps skin fold thickness (mm). This measure can be an indirect indicator of body fat percentage. In some contexts, it's used to infer insulin resistance.
Visualization: Scatter plots to investigate the relationship between skin thickness and BMI or insulin levels; Box plots by Outcome to compare skin thickness in diabetic vs. non-diabetic individuals.

7. Insulin
Explanation: 2-Hour serum insulin (mu U/ml). Insulin levels can help understand insulin resistance or beta-cell function in the pancreas, which is crucial for diabetes management and diagnosis.
Visualization: Histograms to visualize the distribution of insulin levels; Scatter plots to examine the relationship between insulin levels and glucose levels.

9. BMI
Explanation: Body mass index (weight in kg/(height in m)^2). It's a key measure for categorizing individuals as underweight, normal weight, overweight, or obese, with higher values often associated with higher diabetes risk.
Visualization: Box plots to compare BMI across outcomes; Scatter plots to explore the relationship between BMI and glucose levels.

11. Diabetes Pedigree Function
Explanation: A function that scores the likelihood of diabetes based on family history. It reflects the genetic and environmental factors predisposing an individual to diabetes.
Visualization: Box plots to compare Diabetes Pedigree Function scores by Outcome; Scatter plots to see if there's a correlation between this score and glucose levels or age.

13. Age
Explanation: The age of the individual. Age is a risk factor for diabetes, with risk increasing as people get older.
Visualization: Histograms to see the age distribution of the study population; Box plots or Violin plots by Outcome to compare age distributions between diabetic and non-diabetic groups.

15. Outcome
Explanation: The variable indicating whether the individual has diabetes (1) or not (0). This is the dependent variable you are most likely trying to predict or understand through the other variables.
Visualization: Pie charts to show the proportion of individuals with and without diabetes; Bar charts to compare the count of outcomes across different categorical variables.

Suggested Visualizations:
Pairwise Relationships: Use pair plots to visualize the relationships between all continuous variables simultaneously, stratifying by Outcome.
Correlation Heatmap: To visualize the correlation coefficients between all the continuous variables, helping to identify which variables have the strongest relationships with each other and with the Outcome.
Cluster Map: A more advanced visualization, clustering can help identify patterns or groups within the data, potentially uncovering subgroups of individuals with similar profiles regarding their risk of diabetes.

These visualizations can help uncover initial insights, explore hypotheses about diabetes risk factors, and guide further statistical analysis or predictive modeling.
