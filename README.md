## Hemorrhagic Stroke Clinical Intelligent Diagnosis and Treatment Modeling

<img src="https://github.com/user-attachments/assets/f12bf2ec-87cf-4fab-97ea-f3fcec9d5c64" width="450" />
<img src="https://github.com/user-attachments/assets/2e4f64a7-1d6d-4666-af94-026cc0045a1e" width="400" />

### Description:
Hemorrhagic stroke is an acute cerebrovascular disease caused by sudden rupture of blood vessels in the brain or obstruction of blood flow, leading to brain tissue damage. Due to its complex etiology, rapid progression, poor prognosis, and high mortality rate, hemorrhagic stroke imposes a heavy health and economic burden on society and families. Following a hemorrhagic stroke, hematoma expansion is one of the most significant risk factors for poor prognosis, further deteriorating neurological function and even threatening the patient's life. Artificial intelligence (AI) technology assists diagnosis by not only improving diagnostic efficiency and accuracy but also optimizing treatment and prevention plans through big data analysis and machine learning, providing more targeted treatment services for patients. This study aims to analyze and predict two critical events in the aftermath of hemorrhagic **stroke—hematoma** expansion and **peritumoral edema**, as early identification and prediction of these events are vital to improving patient prognosis and quality of life.
#### 1. Exploring Risk Factors of Hematoma Expansion (Problem 1)
The first step was to describe the extent of hematoma expansion in patients and then fit a model based on the training dataset to predict the probability of hematoma expansion in all patients. Feature selection was performed using regression model coefficients, decision tree information gain, and variance contribution rates from **principal component analysis (PCA)**. The final set of **17 features** was selected, and **logistic regression, support vector machine (SVM), and XGBoost models** were fitted. The five-fold cross-validation accuracy for predicting hematoma expansion was 75%, and the probability of hematoma expansion was calculated using the logistic model.
#### 2. Modeling Edema Progression and Treatment Interventions (Problem 2)
For the analysis of edema volume progression over time, a linear equation and a nonlinear equation were constructed for the entire patient population. The residuals were calculated, and the edema growth rate was computed. Using **K-means clustering**, the patients were divided into five subgroups, each fitted with a distinct edema progression curve. The treatment methods significantly influencing edema progression were identified through logistic regression analysis. For example, group 1 was strongly associated with blood pressure-lowering treatment, and group 2 with neuro-nutrition treatment.
#### 3. Prognosis Prediction and Key Factor Exploration (Problem 3)
In this phase, features were selected through feature engineering, and multi-model training was integrated to predict 90-day mRS scores. The cross-validation accuracy for prediction was 63% and 71%, with a tolerance range of 1 (i.e., if the difference between the true value and the predicted value was 1, it was considered correct). Descriptive analysis, including heatmaps, Sankey diagrams, and chord diagrams, revealed a significant correlation between hypertension in male patients and vomiting prevention treatment. Additionally, strong correlations were observed between hematoma and edema volumes in multiple regions of the brain.
### Technologies:
	• Machine Learning Models: Decision Trees, Logistic Regression, Support Vector Machines (SVM), XGBoost
	• Data Preprocessing: Feature Engineering, Principal Component Analysis (PCA)
	• Model Evaluation: Cross-Validation, Performance Metrics (Precision, Recall, etc.)
	• Clustering Algorithms: K-means, DBSCAN
	• Data Visualization: Heatmaps, Sankey Diagrams, Chord Diagrams
	• Programming Languages: Python, R
	• Libraries & Tools: Scikit-learn, Pandas, Matplotlib, XGBoost, TensorFlow
### Skills:
	• Predictive Modeling, Risk Factor Analysis, Treatment Optimization
	• Feature Selection, Model Tuning, Cross-Validation
	• Data Clustering, Statistical Analysis, Data Visualization
	• Healthcare Data Analysis, Artificial Intelligence in Medicine

