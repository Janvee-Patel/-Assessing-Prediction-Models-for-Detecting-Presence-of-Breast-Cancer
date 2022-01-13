# Assessing Prediction Models for Detecting Presence of Breast Cancer

In this project, five statistical prediction models (Random Forest, Support Vector Machine, Logistic Regression, K-Nearest Neighbor, and Adaptive Boosting) were implemented to assess the prediction of obesity-related breast cancer from routine blood measurements. 



Data Source and Paper Citation: 
Patricio, M., Pereira, J., Crisostomo, J., Matafome, P., Gomes, M., Seica,
R., & Caramelo, F. (2018). Using Resistin, glucose, age and BMI to predict the presence of breast cancer.
BMC Cancer, 18(1), 29. https://doi.org/10.1186/s12885-017-3877-1

Additional Relevant Paper Citation: 
Crisostomo, J., Matafome, P., Santos-Silva, D., Gomes, A. L., Gomes,
M., Patrıcio, M., Letra, L., Sarmento-Ribeiro, A. B., Santos, L., & Sei¸ca, R. (2016). Hyperresistinemia and metabolic dysregulation: A risky crosstalk in obese breast cancer. Endocrine, 53(2), 433–442.
https://doi.org/10.1007/s12020-016-0893-x

Data was supplied by UCI Machine Learning Repository

# Repository Contents

PredictionModels_BreastCa_Comibra.Rmd: 

R Markdown file containing code for performing exploratory data analysis of the features, feature selection with recursive feature elimination, and implementing five machine learning algorithms (Random Forest, Support Vector Machine, Logistic Regression, K-Nearest Neighbors, and Adaptive Boosting) using the top 5 features from feature selection and all 9 features. The file also contains code for assessing model performances with AUC/ROC curves, sensitivity, and specificity, and determining performance of a stacked machine learning model with the top 5 features and all 9 features as well. 
