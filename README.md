# Machine Learning Lab Work 2

This repository contains 15 practical programs implementing fundamental machine learning techniques, from data preprocessing and visualization to advanced algorithms including regression, classification, clustering, and dimensionality reduction.

## Programs Overview

### Program 1: Data Exploration and Preprocessing for Housing Data
- Loaded and explored house price dataset with 18 features
- Performed comprehensive data analysis including null value checks and data types
- Created visualizations: correlation heatmap, scatter plots for feature relationships
- Implemented data binning for continuous variables (year built, square footage)
- Applied both Min-Max scaling and Z-score normalization
- Generated box plots to visualize scaled data distributions

**Screenshot**


<img width="496" height="420" alt="image" src="https://github.com/user-attachments/assets/310e1c6b-ee99-40f5-ae19-d381fdbf7d17" />
<img width="505" height="315" alt="image" src="https://github.com/user-attachments/assets/f5054986-23b8-438d-9420-99aaa3a45d5d" />
<img width="479" height="334" alt="image" src="https://github.com/user-attachments/assets/6fb69039-cbb4-442d-85ec-e26fe70131e3" />
<img width="504" height="380" alt="image" src="https://github.com/user-attachments/assets/7f7d0c9a-0b31-4933-acf5-1131bbb06add" />
<img width="477" height="376" alt="image" src="https://github.com/user-attachments/assets/8c990f1b-4927-46f8-8767-f0feb456ad15" />
<img width="474" height="252" alt="image" src="https://github.com/user-attachments/assets/35632c3b-7328-45f1-a9ba-f6616b98b14c" />
<img width="512" height="274" alt="image" src="https://github.com/user-attachments/assets/d602fd10-f09b-4073-b769-5da16bbb4df9" />


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

<img width="526" height="326" alt="image" src="https://github.com/user-attachments/assets/a15260b9-1bdc-479a-8fa7-04c221675fd6" />
<img width="445" height="338" alt="image" src="https://github.com/user-attachments/assets/7d53760f-cdcd-4240-af63-ab0c9e7dfd19" />
<img width="381" height="130" alt="image" src="https://github.com/user-attachments/assets/03849cfd-e07c-43cb-9a96-3478fb20909d" />


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

<img width="432" height="178" alt="image" src="https://github.com/user-attachments/assets/757245b0-8221-4bac-b341-194a6ae707c8" />
<img width="502" height="387" alt="image" src="https://github.com/user-attachments/assets/840eb976-3dd1-4600-8b1e-c7dbcd2c9752" />
<img width="399" height="137" alt="image" src="https://github.com/user-attachments/assets/b340ef44-9bac-48df-96db-bbf086cd2ed6" />
<img width="529" height="385" alt="image" src="https://github.com/user-attachments/assets/1f989564-3813-453f-8f15-27f01d117d35" />


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


<img width="439" height="630" alt="image" src="https://github.com/user-attachments/assets/d8aedc42-45ab-410c-be17-7f5a4e2fedcf" />
<img width="438" height="627" alt="image" src="https://github.com/user-attachments/assets/c0104fac-4319-4dbd-aef9-f7fde165250c" />
<img width="424" height="309" alt="image" src="https://github.com/user-attachments/assets/9b85e85b-3728-461e-808c-0e8ed915b543" />
<img width="343" height="162" alt="image" src="https://github.com/user-attachments/assets/5aeacf4d-9762-4165-b1ba-ad6767fd8ac9" />
<img width="433" height="536" alt="image" src="https://github.com/user-attachments/assets/ca0826a4-e47c-41a3-99b4-863c471b330f" />
<img width="372" height="106" alt="image" src="https://github.com/user-attachments/assets/3b7293a3-c81b-4d0e-b814-b6e734a7c428" />
<img width="433" height="397" alt="image" src="https://github.com/user-attachments/assets/534a6d69-ac63-4f1e-8fa6-dfcccc853ef0" />
<img width="307" height="67" alt="image" src="https://github.com/user-attachments/assets/e475d75a-922a-4215-9e18-d7fc6ee06968" />

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

<img width="513" height="500" alt="image" src="https://github.com/user-attachments/assets/f8417adb-3eb6-438f-871f-93e9aad2ed2c" />
<img width="382" height="41" alt="image" src="https://github.com/user-attachments/assets/bb086235-e5b2-4c9c-b09b-c4c0439f86f7" />
<img width="478" height="516" alt="image" src="https://github.com/user-attachments/assets/6cfdb3a3-e23c-44ae-a8e3-26d0f474f5c0" />




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

<img width="502" height="396" alt="image" src="https://github.com/user-attachments/assets/68ca5e0f-9ad9-433a-8043-3d2b387d6176" />
<img width="524" height="426" alt="image" src="https://github.com/user-attachments/assets/dafdca40-9688-476f-836e-c4832e4663d5" />
<img width="508" height="391" alt="image" src="https://github.com/user-attachments/assets/08721c2e-bce9-434b-879a-f6f0c47c0d06" />
<img width="553" height="534" alt="image" src="https://github.com/user-attachments/assets/6d83cb49-1e97-4535-ae96-79b3395384d0" />




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

<img width="457" height="139" alt="image" src="https://github.com/user-attachments/assets/8c0fb940-c5eb-4da7-96e8-b4d8829e330a" />

---

### Program 8: K-Means Clustering for Obesity Dataset
- Implemented K-Means clustering on obesity dataset with 17 features
- Created cluster visualizations for k=1 to 5
- Applied elbow method to determine optimal number of clusters (k=6)
- Calculated Sum of Squared Errors (SSE) for different k values
- Analyzed cluster distributions and characteristics
- Demonstrated unsupervised learning for pattern discovery in health data

**Screenshot**

<img width="465" height="332" alt="image" src="https://github.com/user-attachments/assets/042086ec-ab04-4fd9-8fbb-e2b342c92901" />
<img width="635" height="281" alt="image" src="https://github.com/user-attachments/assets/2533bd54-6645-40e7-a028-55eab80aa350" />
<img width="543" height="454" alt="image" src="https://github.com/user-attachments/assets/8299dd49-3cbb-4fff-acb2-1e8962902062" />


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

<img width="343" height="141" alt="image" src="https://github.com/user-attachments/assets/d4be8268-01ff-4256-abc0-0f3025220fa3" />
<img width="221" height="178" alt="image" src="https://github.com/user-attachments/assets/c5ae8ba2-468b-4fe1-b9be-bbebaf6b4c86" />
<img width="199" height="157" alt="image" src="https://github.com/user-attachments/assets/a1cded49-107d-4f36-9998-e565ae3b1620" />
<img width="257" height="198" alt="image" src="https://github.com/user-attachments/assets/fb04db88-2fe3-4658-911c-74687bc343fc" />


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

<img width="234" height="352" alt="image" src="https://github.com/user-attachments/assets/2ef47fd4-dcbd-4184-a2d9-f5e49be2d97e" />
<img width="215" height="190" alt="image" src="https://github.com/user-attachments/assets/3d0da170-b174-4761-a5f3-ea201b2bbc7b" />


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

<img width="114" height="160" alt="image" src="https://github.com/user-attachments/assets/811f7c98-9916-4cb5-8871-76b748480e58" />
<img width="254" height="127" alt="image" src="https://github.com/user-attachments/assets/ad01c6d8-11e4-4453-b78b-a5951bc4b047" />
<img width="293" height="204" alt="image" src="https://github.com/user-attachments/assets/caacbd40-9516-43f8-a368-20b29501225c" />


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

<img width="259" height="192" alt="image" src="https://github.com/user-attachments/assets/46580645-2718-44b7-a7c8-c55fa35358f5" />
<img width="244" height="105" alt="image" src="https://github.com/user-attachments/assets/4820216d-b5c4-4ab3-9961-f36fac8f6f0c" />
<img width="140" height="112" alt="image" src="https://github.com/user-attachments/assets/a2292c27-250a-46d0-9b31-a4cc28952d6d" />
<img width="245" height="185" alt="image" src="https://github.com/user-attachments/assets/9c9e1906-7ec7-4812-a011-b3eabee7ebf0" />
<img width="335" height="236" alt="image" src="https://github.com/user-attachments/assets/ece83573-18b5-42b6-a077-4a7256c59af2" />


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

<img width="244" height="119" alt="image" src="https://github.com/user-attachments/assets/9e47a555-1e60-4122-b2fa-9cbce19a5104" />
<img width="248" height="177" alt="image" src="https://github.com/user-attachments/assets/8daf5b77-f08d-45fd-bac6-aa17364a1e5b" />
<img width="242" height="103" alt="image" src="https://github.com/user-attachments/assets/68881ad0-f1fb-4d80-af1f-4a25ded6bbf4" />
<img width="536" height="177" alt="image" src="https://github.com/user-attachments/assets/1f87622d-ef3a-4692-b6a6-2c9357d7509b" />

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

<img width="241" height="162" alt="image" src="https://github.com/user-attachments/assets/01abec95-8f6b-46e7-be98-5764513a3333" />
<img width="226" height="161" alt="image" src="https://github.com/user-attachments/assets/85ae25b0-fbf8-412c-8f7c-c00adae79337" />
<img width="287" height="142" alt="image" src="https://github.com/user-attachments/assets/0848729a-177b-4160-a24e-ec8ce9146dc6" />
<img width="196" height="272" alt="image" src="https://github.com/user-attachments/assets/4352b0c6-a107-47ab-b96c-9c59f2f83386" />
<img width="205" height="105" alt="image" src="https://github.com/user-attachments/assets/6f9f43c6-7490-4f62-ba80-169ac94710d3" />


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

<img width="294" height="189" alt="image" src="https://github.com/user-attachments/assets/18d30fea-783c-4ac2-9648-293858fed0e3" />

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


<img width="313" height="253" alt="image" src="https://github.com/user-attachments/assets/1e411305-1ff1-457b-93c5-5ea8e42a5e21" />
<img width="389" height="261" alt="image" src="https://github.com/user-attachments/assets/79d40d95-d907-41ce-ae44-91a41f620853" />
<img width="391" height="205" alt="image" src="https://github.com/user-attachments/assets/56db16d3-1af1-41c7-b4a7-c5f311f04e95" />
<img width="386" height="289" alt="image" src="https://github.com/user-attachments/assets/bf014b37-2ac2-441b-8683-2c371840050d" />



```

