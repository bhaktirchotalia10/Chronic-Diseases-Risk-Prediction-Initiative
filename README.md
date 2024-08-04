# Chronic-Diseases-Risk-Prediction-Initiative

The Chronic Diseases Risk Prediction Initiative aims to identify and analyze significant lifestyle factors and health behaviors that predict the risk of chronic diseases. Utilizing the Behavioral Risk Factor Surveillance System (BRFSS) data, the project focuses on data discovery, cleaning, and model accuracy optimization to provide insightful outcomes. This initiative focuses on identifying key lifestyle factors and health behaviors that predict chronic disease risks using BRFSS data. The project addresses various challenges from data discovery to model precision, ensuring robust and insightful analysis.

**Project Overview** 

The Chronic Diseases Risk Prediction Initiative utilizes BRFSS data to predict the risk of chronic diseases by identifying significant lifestyle factors and health behaviors. The project overcame challenges in data discovery, cleaning, and model accuracy optimization to achieve reliable and insightful outcomes. Key predictive models include Logistic Regression, Decision Tree, and Random Forest, applied to diabetes and heart disease predictions.

**Data Sources**

We utilized publicly accessible data collected by the United States government, specifically the Behavioral Risk Factor Surveillance System (BRFSS) dataset and WHO Global Health Observatory data.

This dataset includes variables relevant to public health surveys, focusing on individual health statuses and behaviors designed for comprehensive health risk assessment.
1. Demographics: Details like state residence, gender, and household composition.
2. Health Behaviors: Information on exercise, sleep, dental visits, and alcohol and tobacco use.
3. Health Conditions: Data on common and serious diseases, including diabetes, cancer, heart conditions, and mental health.
4. Socioeconomic Factors: Income, employment, and housing data.

Link: https://www.cdc.gov/brfss/annual_data/annual_2022.html 

**Modeling Techniques**

**Diabetes Prediction** - For diabetes prediction, we started with Logistic Regression due to its interpretability and effectiveness in binary classification tasks. Despite its simplicity, it served as a baseline model. We then employed Decision Trees to better capture non-linear relationships. Hyperparameters were optimized using GridSearchCV to enhance model performance. Finally, we applied Random Forest models, leveraging ensemble learning to further improve predictive accuracy. Each model was carefully tuned to balance complexity and interpretability.

**Heart Disease Prediction** - For heart disease prediction, we also began with Logistic Regression, acknowledging its limitations in modeling complex non-linear relationships. Next, Decision Trees were used to better understand interactions between variables, with hyperparameter optimization via GridSearchCV. Lastly, Random Forest models were employed to utilize ensemble learning, which provided robustness against overfitting and improved overall predictive power.

**Results**

**Diabetes Prediction** - The Logistic Regression model for diabetes achieved a training accuracy of 85%, but the F1 score on test data was relatively low, indicating limitations in capturing non-linear relationships. The Decision Tree model, after optimization, demonstrated a test accuracy of 85% and an F1 score of 0.92, showing significant improvement. The Random Forest model reached a test accuracy of 85% and a weighted F1 score of 0.80, highlighting its effectiveness in predicting diabetes risk factors.

**Heart Disease Prediction** - In predicting heart disease, the Logistic Regression model achieved a training accuracy of 91%, but struggled with modeling complex relationships, reflected in a low F1 score. The optimized Decision Tree model excelled with a test accuracy of 94% and an F1 score of 0.97, demonstrating its ability to handle non-linear interactions effectively. The Random Forest model for heart disease prediction showed a test accuracy of 93% and a weighted F1 score of 0.91, confirming its robustness and superior performance in predicting heart disease risks.

**Learnings from the Project**

**1. Data Quality is Crucial:** Ensuring complete and accurate data is essential for reliable predictions. Addressing missing values and inconsistencies improves model robustness.

**2. Effective Model Selection:** Different models like Logistic Regression, Decision Trees, and Random Forests offer unique benefits. Selecting and optimizing the right model is key for accurate predictions.

**3. High-Risk Segment Identification:** Identifying demographic and behavioral risk factors enables targeted health interventions and improved public health strategies.

**4. Feature Engineering Impact:** Creating and selecting relevant features significantly enhance model performance and predictive power.

**5. Managing Data Challenges:** Overcoming data volume and quality issues is crucial for maintaining the integrity of the analysis.

**6. Actionable Insights:** Translating predictive model results into practical health policies and preventive measures can effectively reduce the burden of chronic diseases.


