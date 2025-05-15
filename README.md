#   Spaceship Titanic: Predicting Interdimensional Passenger Transport 🚀🌌

###   Project Overview 🧑‍💻

In this project, I developed a classification model to predict whether passengers aboard the Spaceship Titanic were transported to another dimension. This was a fascinating challenge that required careful data preprocessing, exploratory data analysis, and the application of various machine learning algorithms. 🤖

###   Key Objectives 🎯

* Accurately classify passengers as "Transported" or "Not Transported." ✅
* Utilize machine learning techniques to understand the factors influencing transportation. 🧠
* Achieve high accuracy in predictions using robust models. 📈

###   Data Description 📊

The dataset includes passenger information with a split of approximately 2/3 for training (8693 entries) and 1/3 for testing (4277 entries). The training set contains 14 attributes, while the test set has 13 attributes (missing the target variable, "Transported").

* **Numerical Attributes**: 6 (e.g., Age 🔢, RoomService 💰, FoodCourt 🍔)
* **Categorical Attributes**: 5 (e.g., HomePlanet 🌎, CryoSleep 💤, Cabin 🛏️)

###   Data Preprocessing 🛠️

* **Missing Values**: Handled by imputing with the mean for 'Age' and 0 for monetary attributes. Categorical missing values were filled with the mode. 🧽
* **Feature Encoding**: Categorical variables were encoded to numerical format for model compatibility. ➡️
* **Feature Scaling**: Numerical features were scaled to standardize the data. ⚖️

###   Exploratory Data Analysis (EDA) 🔍

* **Transportation Insights**:

    * Passengers from Europa had a 66% chance of being transported. 👽
    * Passengers from Earth had a 60% chance of not being transported. 🌍
    * Passengers in CryoSleep had an 82% chance of being transported. ❄️
* **Age Distribution**: Most passengers were between 15-30 years old. 🎂
* **Spending Patterns**: Transported passengers tended to spend less on amenities. 💸

###   Modeling 🤖

I employed a variety of classification algorithms:

* K-Nearest Neighbors
* Logistic Regression
* Naive Bayes
* Decision Tree 🌳
* Random Forest 🌲
* Extreme Gradient Boosting (XGBoost)
* Light Gradient Boosting Machine (LGBM) ⚡
* Gradient Boosting
* Neural Network (Multi-Layer Perceptron) 🧠

The Light Gradient Boosting Machine (LGBM) Classifier performed the best. ✨

###   Results 🏆

* The Light Gradient Boosting Machine (LGBM) Classifier was the most accurate model. 🥇
* Achieved a cross-validation accuracy of 79.32% on the training data. 💯
* The model's accuracy on the test data was 78.98%. 🎯

###   Conclusion 🎉

This project successfully classified passengers with high accuracy. The insights gained from EDA highlight significant factors influencing passenger transportation. Further improvements could be achieved through hyperparameter tuning and additional feature engineering. 🚀

###   Tech Stack 💻

* Python 🐍
* Pandas, Numpy 🐼
* Matplotlib, Seaborn 📊
* Scikit-learn 🔬
* LightGBM, XGBoost ⚡
