# Prediction and Analysis using SVM
This project involves using Support Vector Machines (SVM) to predict and analyze a diabetes dataset. The key points are:

* The dataset contains 768 instances with 9 features including Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age. The target variable is Outcome (0 or 1 for no diabetes or diabetes).
* The analysis includes data cleaning, handling missing values, univariate and pairwise visualizations to understand the feature distributions and relationships.
* A GridSearchCV was used to tune the hyperparameters of the SVM model, including the regularization parameter C and the kernel function. The best model achieved a test set accuracy of 73.4%.
* The model performs reasonably well, but has room for improvement. It could potentially be used as a supporting tool in the medical industry to assist in diabetes diagnosis, though further refinement and validation would be needed.
