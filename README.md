**🏠 House Price Prediction - Linear and Multiple Regression**

**1. 📌 Objective**
Implement and understand simple and multiple linear regression.
Predict house prices based on various features (area, number of bedrooms, amenities, etc.).
Evaluate model performance using standard regression metrics.
Visualize the regression results and interpret model coefficients.

**2. 🛠 Tools and Libraries Used**
Python 3.x
Pandas → Data loading, cleaning, and preprocessing.
Scikit-learn → Linear regression modeling and evaluation metrics.
Matplotlib → Visualization of regression lines and results.
Seaborn (optional) → For advanced visualizations (correlation matrices, heatmaps).

**3. 🔄 Step-by-Step Process**
   
**3.1 Import and Preprocess the Dataset**
Load the dataset using Pandas.
Handle column name corrections (hotwaterheating).
Map binary features (e.g., yes/no) to 0 and 1.
One-hot encode furnishingstatus.
Check and handle missing values.

**3.2 Split the Data into Train and Test Sets**
Split the dataset into 80% training and 20% testing.
Used train_test_split from Scikit-learn with a random state for reproducibility.

**3.3 Fit a Linear Regression Model**
Initialize LinearRegression() from sklearn.linear_model.
Train the model on training data (X_train, y_train).
Predict on test data (X_test).

**3.4 Evaluate the Model**
Evaluation metrics used:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score (Coefficient of Determination)

**3.5 Plot the Regression Line and Interpret Coefficients**
For simple linear regression (like Area vs Price):
Plot scatter points.
Plot the regression line fitted by the model.

**Interpret the coefficients:

Positive coefficient → feature increases price.

Negative coefficient → feature decreases price.**

**4. 📈 Inferences and Conclusion**

Area, bathrooms, and air conditioning showed the strongest positive relationships with price.

Amenities like basement and guestroom availability also significantly influenced house prices.

A good R² score indicated that the model explained a substantial part of the variability in house prices.

Minor multicollinearity was observed between features like area and stories, which can be improved later.


