# Machine Learning Lab Work 2

This repository contains 16 practical programs implementing fundamental machine learning techniques, from data preprocessing and visualization to advanced algorithms including regression, classification, clustering, and dimensionality reduction.

## Programs Overview

### Program 1: Data Exploration and Preprocessing for Housing Data
- Loaded and explored house price dataset with 18 features
- Performed comprehensive data analysis including null value checks and data types
- Created visualizations: correlation heatmap, scatter plots for feature relationships
- Implemented data binning for continuous variables (year built, square footage)
- Applied both Min-Max scaling and Z-score normalization
- Generated box plots to visualize scaled data distributions

**Screenshot**


<img width="488" height="418" alt="image" src="https://github.com/user-attachments/assets/d17f3f7d-6356-4843-92aa-d31569683351" />
<img width="494" height="309" alt="image" src="https://github.com/user-attachments/assets/f306f29d-d62b-4af1-bacd-c405837c2aab" />
<img width="452" height="311" alt="image" src="https://github.com/user-attachments/assets/3d4626d6-c6b5-452e-98de-0caa36a80cb3" />
<img width="525" height="389" alt="image" src="https://github.com/user-attachments/assets/eb3306ed-2d05-42ee-99cc-e3c11f05f5fb" />
<img width="460" height="261" alt="image" src="https://github.com/user-attachments/assets/348282fe-ac0b-413e-9c54-7cef26deca41" />



---

### Program 2: Linear Regression for Housing Value Prediction
- Implemented simple linear regression on Boston housing dataset
- Used Avg_rooms as predictor for MValue (median home value)
- Applied Z-score method for outlier detection and removal
- Split data into training (70%) and testing (30%) sets
- Calculated regression coefficients and intercept
- Evaluated model performance using MSE and R-squared metrics
- Achieved R² of 0.516 on training and 0.554 on testing data

**Screenshot**

<img width="469" height="346" alt="image" src="https://github.com/user-attachments/assets/9f77d4cb-166f-4f84-af41-9866f24a7760" />
<img width="462" height="333" alt="image" src="https://github.com/user-attachments/assets/02e2818f-b750-4353-a844-a44627fd7481" />
<img width="490" height="208" alt="image" src="https://github.com/user-attachments/assets/549fe267-ebe3-479f-9fa0-3c40efe391b1" />



---

### Program 3: Logistic Regression for Binary Classification
- Implemented logistic regression on bank marketing dataset
- Used duration, age, and campaign features for subscription prediction
- Created pair plots for feature-target visualization
- Achieved 89.5% accuracy on test data
- Generated comprehensive classification reports and confusion matrices
- Extended analysis to banknote authentication dataset with 99% accuracy
- Compared performance across different classification problems

**Screenshot**

<img width="409" height="142" alt="image" src="https://github.com/user-attachments/assets/918e8935-641f-47de-8394-fe1e2273bce3" />
<img width="499" height="395" alt="image" src="https://github.com/user-attachments/assets/4988b8c5-9fed-45dc-bf78-8ee453a1c6e2" />
<img width="420" height="158" alt="image" src="https://github.com/user-attachments/assets/1e11e404-4a48-4a5e-84c8-3f3106352181" />
<img width="512" height="371" alt="image" src="https://github.com/user-attachments/assets/4b2388b6-2c12-45ad-8dba-77cb200e8324" />



---

### Program 4: Advanced Regression Techniques for Medical Data
- Analyzed liver patient dataset with 14 medical parameters
- Handled missing values using mean imputation
- Implemented simple linear regression (CREA vs PROT)
- Calculated VIF to detect multicollinearity among features
- Built multiple linear regression with 5 selected features
- Implemented polynomial regression (degrees 2, 3, 4)
- Applied Ridge and Lasso regression with GridSearchCV for hyperparameter tuning
- Compared model performance using adjusted R-squared metrics

**Screenshot**

<img width="483" height="694" alt="image" src="https://github.com/user-attachments/assets/1ee202bc-fd43-4417-97b2-8e6dac6c8582" />
<img width="465" height="700" alt="image" src="https://github.com/user-attachments/assets/898a7efc-bea9-40ab-a06d-be8c01256a0e" />
<img width="526" height="453" alt="image" src="https://github.com/user-attachments/assets/8fce0208-0468-4314-99de-a42722f60b74" />
<img width="504" height="461" alt="image" src="https://github.com/user-attachments/assets/b0f6a4c1-417d-4cc3-b77e-74051345db0d" />
<img width="508" height="87" alt="image" src="https://github.com/user-attachments/assets/9f822170-9b5d-40cb-9701-28080b1de78b" />



---

### Program 5: Multiple Linear Regression and Multicollinearity Analysis
- Analyzed computer repair time dataset
- Implemented multiple linear regression with two predictors
- Calculated correlation between independent variables
- Computed R-squared and adjusted R-squared values
- Applied Variance Inflation Factor (VIF) to detect multicollinearity
- Demonstrated impact of correlated predictors on regression models
- Built predictive model for repair time estimation

**Screenshot**

<img width="483" height="473" alt="image" src="https://github.com/user-attachments/assets/9dab1354-6509-469d-8007-f3c52d4411c1" />

<img width="491" height="276" alt="image" src="https://github.com/user-attachments/assets/3839e227-be79-49b2-b9da-2f1914940394" />




---

### Program 6: Polynomial Regression for Atmospheric Data
- Implemented polynomial regression on weather dataset
- Used Temperature to predict Pressure
- Tested polynomial degrees 2 through 7 with different train-test splits
- Evaluated models using R-squared, MSE, and MAE metrics
- Visualized polynomial fits against actual data points
- Identified optimal polynomial degree (5) with 70.4% R-squared
- Demonstrated overfitting with higher polynomial degrees

**Screenshot**


<img width="366" height="287" alt="image" src="https://github.com/user-attachments/assets/83d1d3bd-6455-40c5-b995-ff12875b1613" />

<img width="438" height="325" alt="image" src="https://github.com/user-attachments/assets/f5b96aca-88e4-4d80-ad00-c0caacc917d2" />

<img width="432" height="342" alt="image" src="https://github.com/user-attachments/assets/a2923230-441c-47ca-9f87-111651ea4c89" />

<img width="430" height="524" alt="image" src="https://github.com/user-attachments/assets/0720f0d6-d44a-41f7-91d2-61d6e0388809" />





---

### Program 7: Dimensionality Reduction with PCA and LDA
- Applied PCA and LDA on three datasets: Iris, Breast Cancer, and Diabetes
- Reduced feature dimensions while preserving variance
- Compared classifier performance (KNN, Decision Tree, Random Forest) before and after reduction
- Calculated explained variance ratios for principal components
- Generated scatter plots for reduced dimensional spaces
- Provided comprehensive performance comparison across datasets
- Demonstrated trade-offs between dimensionality reduction and model accuracy

**Screenshot**


<img width="510" height="326" alt="image" src="https://github.com/user-attachments/assets/8ccb94ef-ae90-4411-888b-c12dec436388" />


---

### Program 8: K-Means Clustering for Obesity Dataset
- Implemented K-Means clustering on obesity dataset with 17 features
- Created cluster visualizations for k=1 to 5
- Applied elbow method to determine optimal number of clusters (k=6)
- Calculated Sum of Squared Errors (SSE) for different k values
- Analyzed cluster distributions and characteristics
- Demonstrated unsupervised learning for pattern discovery in health data

**Screenshot**


<img width="463" height="301" alt="image" src="https://github.com/user-attachments/assets/36a6dd35-558c-45cc-9e3b-308809945aa5" />

<img width="432" height="213" alt="image" src="https://github.com/user-attachments/assets/1a622301-47a1-4885-997a-477789b09848" />

<img width="470" height="373" alt="image" src="https://github.com/user-attachments/assets/0fb4d3d0-dc44-4b87-882b-9100db72fe1e" />



---

### Program 9: Simple Linear Regression and Model Comparison
- Implemented computer repair time prediction using linear regression
- Created and compared three speculative models
- Calculated error metrics (SSE) for model evaluation
- Derived best-fit line using least squares method
- Compared manual calculation with scikit-learn implementation
- Computed SST, SSE, SSR, and R-squared values
- Achieved R-squared of 0.987 for the best-fit model

**Screenshot**


<img width="452" height="314" alt="image" src="https://github.com/user-attachments/assets/6a2674ec-f0ab-44b8-b106-ac1382bd13be" />

<img width="421" height="343" alt="image" src="https://github.com/user-attachments/assets/cb832b50-afc7-4bfa-becb-ee6f58881190" />

<img width="442" height="331" alt="image" src="https://github.com/user-attachments/assets/62583b81-9290-4944-ad46-9a1f7ae9ce8d" />

<img width="497" height="318" alt="image" src="https://github.com/user-attachments/assets/905ac0c8-35e1-454e-9320-dbfe3c6d7e3f" />


---

### Program 10: Comprehensive Regression Analysis Pipeline
- Implemented complete regression analysis pipeline on medical data
- Handled missing values and performed data visualization
- Applied VIF for multicollinearity detection
- Built multiple regression models with feature selection
- Implemented polynomial regression with degree optimization
- Applied regularization techniques (Ridge and Lasso)
- Compared model performance using adjusted R-squared metrics

**Screenshot**


<img width="494" height="613" alt="image" src="https://github.com/user-attachments/assets/ff972c44-9d08-40ec-88f5-4a3436291d32" />

<img width="490" height="158" alt="image" src="https://github.com/user-attachments/assets/614ba0ac-b8ce-4606-9745-82ed151a4d2e" />



---

### Program 11: Dimensionality Reduction and Classification Comparison
- Comprehensive analysis of PCA and LDA on three datasets
- Visualized reduced dimensions using scatter plots
- Compared KNN, Decision Tree, and Random Forest classifiers
- Generated confusion matrices and performance metrics
- Provided conceptual interpretation of dimensionality reduction results
- Demonstrated when to use PCA vs LDA for different data types
- Analyzed trade-offs between feature reduction and classification accuracy

**Screenshot**


<img width="471" height="444" alt="image" src="https://github.com/user-attachments/assets/669589de-75c8-43be-8676-7a47d472e352" />

<img width="572" height="424" alt="image" src="https://github.com/user-attachments/assets/9ff5f7dc-1b2b-4992-b74a-633e258bb2d4" />

<img width="558" height="512" alt="image" src="https://github.com/user-attachments/assets/c09d2145-9747-4df4-9d59-c7717973afca" />

<img width="506" height="500" alt="image" src="https://github.com/user-attachments/assets/7ad03cf6-2871-4090-8334-be53116d024f" />



---

### Program 12: Neural Network Fundamentals and Perceptron Implementation
- Implemented various activation functions: Unit Step, Signum, Linear, Piece-wise, Sigmoid, Tanh
- Applied activation functions to Iris dataset features
- Created MLP classifier for Iris classification with 96.67% accuracy
- Built perceptron for logic gates (AND, OR, XOR operations)
- Demonstrated perceptron limitations on non-linearly separable data (XOR)
- Visualized neural network decision boundaries
- Generated confusion matrices for performance evaluation

**Screenshot**


<img width="540" height="373" alt="image" src="https://github.com/user-attachments/assets/2b7d181d-cf35-457a-a377-925144a84f49" />

<img width="448" height="152" alt="image" src="https://github.com/user-attachments/assets/cc5542c2-56ca-418c-93ce-eea2f8712593" />

<img width="534" height="430" alt="image" src="https://github.com/user-attachments/assets/5c9b99c7-e37f-482d-ae46-8095082b6b27" />

<img width="452" height="326" alt="image" src="https://github.com/user-attachments/assets/7436cb90-4610-4859-bdf8-9da9f84d85df" />



---

### Program 13: Bank Marketing Classification with Logistic Regression
- Analyzed bank marketing dataset with 21 features and 41,188 instances
- Performed data preprocessing and categorical encoding
- Implemented feature scaling using StandardScaler
- Built logistic regression model with regularization (C=10)
- Achieved 91.05% accuracy on test data
- Demonstrated complete machine learning pipeline from preprocessing to evaluation
- Handled large-scale real-world dataset with mixed data types

**Screenshot**


<img width="550" height="422" alt="image" src="https://github.com/user-attachments/assets/4440201c-11df-4060-baff-7de4edb45f10" />

<img width="554" height="385" alt="image" src="https://github.com/user-attachments/assets/8ace4d78-f2e6-4aaa-a348-7b5f4a6dde24" />

<img width="591" height="338" alt="image" src="https://github.com/user-attachments/assets/905888ba-6e62-4c73-ab3a-24999a5536e4" />


---

### Program 14: Clustering Algorithms and Evaluation
- Generated synthetic 2D dataset for clustering analysis
- Implemented K-Means clustering with k ranging from 2 to 10
- Calculated within-cluster sum of squares for each k
- Computed silhouette scores for cluster quality assessment
- Applied hierarchical clustering with three linkage methods (ward, complete, average)
- Visualized clusters and dendrograms for different algorithms
- Compared clustering performance using silhouette scores
- Demonstrated elbow method for optimal k selection

**Screenshot**


<img width="440" height="323" alt="image" src="https://github.com/user-attachments/assets/d1bcc556-cef9-4def-bc66-6ad50713f307" />

<img width="457" height="455" alt="image" src="https://github.com/user-attachments/assets/6d8941b7-0745-4eea-a36c-9ae8e4c0fe1e" />

<img width="454" height="510" alt="image" src="https://github.com/user-attachments/assets/41603e4c-67c9-4172-878b-583316554b6f" />

<img width="466" height="525" alt="image" src="https://github.com/user-attachments/assets/4b025957-4ecd-4ec5-becd-e18a9083c76a" />

<img width="465" height="512" alt="image" src="https://github.com/user-attachments/assets/df9bb2f5-e580-4ca8-8799-2793ab68aff7" />

<img width="507" height="337" alt="image" src="https://github.com/user-attachments/assets/2aef65b0-b36a-48e3-a49b-d23d8c67548d" />



---

### Program-15: Dimensionality Reduction with PCA for Classification
- Applied PCA on banknote authentication dataset
- Reduced 4 features to 2 principal components
- Compared Decision Tree performance before and after PCA
- Achieved 98.06% accuracy on original features vs 82.04% on PCA features
- Analyzed information loss vs dimensionality reduction trade-off
- Demonstrated PCA application in real-world classification problems
- Generated performance comparison reports

**Screenshot**


<img width="458" height="160" alt="image" src="https://github.com/user-attachments/assets/a947d32f-d0b0-4153-8fc2-5c49725ab4ff" />

<img width="460" height="222" alt="image" src="https://github.com/user-attachments/assets/cae13203-a539-4ffb-9599-c190737bb3c5" />


---

### Program-16: Comprehensive Regression Project - Water Potability Prediction
- Comprehensive water quality analysis with multiple algorithms
- Handled missing values using conditional imputation
- Built Logistic Regression and Decision Tree classifiers
- Evaluated models using accuracy, precision, recall, and F1-score
- Generated confusion matrices and performance reports
- Achieved 71.19% accuracy with Decision Tree classifier
- Provided insights on model selection for imbalanced datasets
- Demonstrated complete regression analysis pipeline

**Screenshot**



<img width="492" height="388" alt="image" src="https://github.com/user-attachments/assets/4a606808-d531-40d3-ad71-47355af2ae20" />

<img width="625" height="530" alt="image" src="https://github.com/user-attachments/assets/27ac1c2a-0b3b-4f33-af8d-bfdc3c35bd58" />

<img width="529" height="278" alt="image" src="https://github.com/user-attachments/assets/9a2c6d2b-9b44-4ad2-bd9e-809caa6bcd5d" />

<img width="635" height="439" alt="image" src="https://github.com/user-attachments/assets/db133fa5-12a7-490a-a759-54f9d033904c" />

<img width="643" height="444" alt="image" src="https://github.com/user-attachments/assets/731f93ea-4117-4a71-abb0-d957e5ee6f96" />




```

