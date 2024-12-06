# Diabetes-Health-Indicators
<p>When discussing ML projects related to diabetes, key health indicators often include: Body Mass Index (BMI), age, blood pressure, cholesterol levels, fasting blood glucose, family history of diabetes, waist circumference, physical activity level, smoking status, and sometimes even socioeconomic factors; these variables are used to build machine learning models that can predict the risk of developing diabetes or identify individuals who might be prediabetic, enabling early intervention and preventative measures</p>

<p>The Diabetes Health Indicators Dataset contains healthcare statistics and lifestyle survey information about people in general along with their diagnosis of diabetes. The 35 features consist of some demographics, lab test results, and answers to survey questions for each patient. The target variable for classification is whether a patient has diabetes, is pre-diabetic, or healthy</p>

<h1>Dataset Information</h1>
<h3>For what purpose was the dataset created?</h3>

<p>To better understand the relationship between  lifestyle and diabetes in the US</p>

<h3>Who funded the creation of the dataset?</h3>

<p>The CDC</p>

<h3>What do the instances in this dataset represent?</h3>

<p>Each row represents a person participating in this study.</p>

<h3>Are there recommended data splits?</h3>

<p>Cross validation or a fixed train-test split could be used.</p>

<h3>Does the dataset contain data that might be considered sensitive in any way?</h3>

- Gender
- Income
- Education level
<h2>Additional Variable Information</h2>

- Diabetes diagnosis
- Demographics (race, sex)
- Personal information (income, educations)
- Health history (drinking, smoking, mental health, physical health)

<h3>Class Labels</h3>

- Diabetes
- Pre-diabetes
- Healthy

<h1>Key points about diabetes health indicators in ML projects:</h1>
<h3>Commonly used metrics:</h3>
<ul>
  <li>BMI: A measure of body fat based on height and weight, often considered one of the most significant indicators for diabetes risk. </li>
  <li>Fasting blood glucose: A blood sugar level measured after a period of fasting, directly indicating potential diabetes presence.  </li>
  <li>Blood pressure: High blood pressure can be a contributing factor to diabetes risk.  </li>
  <li>Age: Older individuals tend to have a higher risk of developing diabetes. </li>
  <li>Family history: Having a family member with diabetes increases personal risk.  </li>
  <li>Waist circumference: A measure of abdominal fat, which is particularly linked to diabetes risk.</li>
  
</ul>

<h3>ML model types:</h3>
<ul>
  <li>Logistic regression: Useful for predicting the probability of a binary outcome (like diabetes diagnosis) based on several input variables. </li>
  <li>Decision trees: Can visualize the decision-making process and identify important features. </li>
  <li>Random Forests: An ensemble of decision trees, often providing better prediction accuracy. </li>
  <li>Support Vector Machines (SVM): Can effectively handle complex, non-linear relationships between features. </li>
   <li>KNN: Can effectively handle complex, non-linear relationships between features. </li>
   <li>Naive-Bayes: Can effectively handle complex, non-linear relationships between features. </li>
</ul>




