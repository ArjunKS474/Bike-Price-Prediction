# Bike Price Prediction Using Linear Regression

This project aims to predict the selling price of bikes using linear regression analysis based on various features. By leveraging these features, the goal is to develop a model that accurately estimates the selling price of bikes in the used market.

# Dataset

The dataset used for this project includes the following columns:
- Brand: Brand of the bike
- Model: Model of the bike
- Selling_Price: Selling price of the bike (target variable)
- Year: Year of purchase
- Seller_Type: Type of seller (Individual or Dealer)
- Owner: Ownership history (e.g., 1st owner, 2nd owner)
- KM_Driven: Kilometers driven by the bike
- Ex_Showroom_Price: Ex-showroom price of the bike when new

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Steps:

**1. Data Preprocessing**
- Load the dataset.
- Handle missing values by imputing or removing them.
- Encode categorical variables if necessary (e.g., Brand, Seller_Type).
  
**2. Feature Selection**
- Analyze the features and their correlation with the selling price.
- Select features that significantly impact the bike's selling price
  
**3. Model Training**
- Split the data into training and testing sets.
- Train the linear regression model using the training set.
- Fine-tune hyperparameters to optimize model performance.
  
**4. Model Evaluation**
- Use the testing set to evaluate the model.
- Measure metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess model accuracy.
- Visualize predictions versus actual selling prices.

# Conclusion

Linear regression proves effective in predicting bike selling prices based on various features, providing valuable insights for buyers and sellers in the used bike market. This model can facilitate informed decision-making and price negotiations.
