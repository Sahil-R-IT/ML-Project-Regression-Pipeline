### &nbsp;		ML Regression Pipeline

A complete EDA-to-Modeling workflow using Decision Tree, Random Forest, KNN, and Support Vector Regression



#### 

#### 📌 Overview



This project examines how various regression algorithms learn from data and perform under different levels of complexity.

The pipeline covers data cleaning, preprocessing, EDA, model training, and performance comparison using four popular machine learning models.



The goal was not only to achieve strong predictive performance but to deepen understanding of how algorithm choice impacts real-world results.





#### 🎯 Objectives



Build a complete machine learning workflow



Explore data patterns through EDA



Train and compare four regression models



Evaluate and interpret model performance



Strengthen intuition behind algorithm selection





#### 🧰 Tech Stack



Python



Pandas, NumPy



Matplotlib, Seaborn



Scikit-learn



Jupyter Notebook





#### 🔍 Project Workflow



###### 1️⃣ Data Loading \& Cleaning



Handle missing values



Fix inconsistent data types



Remove outliers where necessary



###### 2️⃣ Exploratory Data Analysis (EDA)



Correlation heatmaps



Distribution plots



Feature relationships



Outlier and noise detection



###### 3️⃣ Preprocessing



Feature scaling



Train-test split



Normalization for distance-based and kernel models



###### 4️⃣ Model Implementation



The following models were trained and evaluated:

\# Decision Tree Regressor

from sklearn.tree import DecisionTreeRegressor

dt\_model = DecisionTreeRegressor(max\_depth=5)



\# Random Forest Regressor

from sklearn.ensemble import RandomForestRegressor

rf\_model = RandomForestRegressor(n\_estimators=100)



\# KNN Regressor

from sklearn.neighbors import KNeighborsRegressor

knn\_model = KNeighborsRegressor(n\_neighbors=5)



\# Support Vector Regression

from sklearn.svm import SVR

svr\_model = SVR()





###### 5️⃣ Model Evaluation



Performance metrics used:



Mean Absolute Error (MAE)



Mean Squared Error (MSE)



R² Score



Cross-validation performance



#### 📊 Results Summary



|      Model        |          Strengths              |          Weaknesses              |

| ----------------- | ------------------------------- | -------------------------------- |

|   Decision Tree   | Easy to interpret, fast         | Overfits easily                  |

|   Random Forest   | Best generalization, stable     | Slower training                  |

|   KNN Regressor   | Simple, captures local patterns | Sensitive to scaling             |

|   SVR             | Handles non-linear patterns     | Needs tuning, slow on large data |



Random Forest achieved the most consistent and reliable performance, while SVR showed strong results with proper scaling and tuning.



#### 💡 Key Learnings



Preprocessing dramatically affects model performance



Ensemble methods reduce variance and improve generalization



Distance-based models require careful scaling



Kernel methods can outperform others with the right parameters



EDA is essential before selecting or tuning models



