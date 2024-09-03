# Recipe-For-rating-Predict-Food-Rating-Using-ML
This is the project in part of curriculam in Bsc in data Science at IIT Madras. it is comes under the Machien Learning Course and Machine Learning techniques Course. in this project  we have to build the model which can predict the rating according to user behavoiurs.

**Columns Description**

- RecipeNumber: Placement of the recipe on the top 100 recipes list

- RecipeCode: Unique ID of the recipe used by the site

- RecipeName: Name of the recipe the comment was posted on

- CommentID: Unique ID of the comment

- UserID: Unique ID of the user who left the comment

- UserName: Name of the user

- UserReputation: Internal score of the site, roughly quantifying the past behavior of the user

- CreationTimestamp: Time at which the comment was posted as a Unix timestamp

- ReplyCount: Number of replies to the comment

- ThumbsUpCount: Number of up-votes the comment has received

- ThumbsDownCount: Number of down-votes the comment has received

- Rating: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable)

- BestScore: Score of the comment, likely used by the site to help determine the order comments appear in

- Recipe_Review: Text content of the comment

# 🚀 Project Overview 🚀

**In my latest project, I tackled the challenge of predicting user ratings of food in restaurants. Leveraging a comprehensive workflow, I conducted a thorough data overview, delved into exploratory data analysis (EDA), and rigorously cleaned and preprocessed the dataset.**

- Comprehensive Workflow: Carried out a detailed project workflow that included data overview, exploratory data analysis (EDA), and rigorous data cleaning and preprocessing.

- Data Preprocessing: Applied Simple Imputer for filling missing values. Used StandardScaler and MinMaxScaler for scaling numerical data. Leveraged Pipeline and Column Transformer API for efficient processing.

- Categorical Data Transformation: Utilized TF-IDF Vectorizer and CountVectorizer for effective categorical data transformation.

- Data Balancing: Implemented SMOTE API to balance the dataset. 

# Model Development: 
Created a classification model utilizing Logistic Regression, SVM, Perceptron, and ensemble methods, and Xgboost achieving up to 78.9% accuracy, with peak performance close to 80%.

# Performance Optimization: 
Applied feature engineering and hyperparameter tuning techniques to maximize model accuracy.

# Models Evaluated:
1. **Logistic regression**
   - Accuracy 78.9%
2. **Support Vector Classifier (SVC)**
   - Accuracy 78.6%
3. **XGB Classifier**
   - Accuracy 78.02%
4. **Random Forest**
   - Accuracy 77.2%
5.** K-Nearest Neighbors (KNN)**
   - Accurcay 77.5%
# Technologies Used
   - Python: The primary programming language used for data manipulation and model training.
   - Jupyter Notebook: For interactive coding and documenting the workflow.
   - Pandas: For data loading and preprocessing.
   - Scikit-learn: For model training and evaluation.
   - Seaborn and Matplotlib: For data visualization and plotting model comparison graphs.

# Achievement: 
Secured 29th rank in a Kaggle competition
# Contact Information
- **Name:** Amit Kumar
- **LinkedIn:** [Amit Kumar](https://www.linkedin.com/in/amit-kumar83/)


