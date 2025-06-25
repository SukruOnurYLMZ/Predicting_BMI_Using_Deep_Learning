# Predicting_BMI_Using_Deep_Learning
BMI Deep Learning

🧠 Capstone Project: Predicting BMI Using Deep
Learning
🔄From Machine Learning to Deep Learning
Previously, you completed this capstone project using classical regression techniques. Your
goal was to predict Body Mass Index (BMI) using features such as height, weight, age,
exercise frequency, and other human attributes.
In that project, you successfully:
• Conducted Exploratory Data Analysis (EDA),
• Built and evaluated models such as:
o Simple Linear Regression (with a single feature),
o Multiple Linear Regression (using all features),
o Ridge, Lasso, and Elastic Net Regression,
• Identified multicollinearity,
• Tuned hyperparameters,
• Interpreted feature impacts.
🚀Now: Deep Learning Implementation
Your current task is to reproduce the entire end-to-end project, but this time using a Deep
Learning approach with Artificial Neural Networks (ANNs).
You will follow the same structure and workflow as in the Machine Learning version:
• Same dataset
• Same target variable (BMI)
• Same core steps (EDA, preprocessing, modeling, evaluation, and reporting)
But instead of regression models like Ridge or Lasso, you will:
• Design and train a neural network using Keras or PyTorch
• Apply activation functions like ReLU or Others
• Compile with a regression loss function such as Mean Squared Error (MSE)
• Optimize using methods like RMSprop or Adam
• Monitor training and validation loss across epochs
✅Required: Replicate All Applications from Notebook 1
You are expected to include every key task from your previous submission, but adapted
for deep learning:
• Re-run the same EDA visualizations and correlation analyses
• Apply appropriate feature scaling and encoding
• Split the dataset exactly as before (80/20)
• Evaluate your deep learning model using the same metrics:
o R² Score
o MAE, MSE, RMSE
• Visualize results:
o Actual vs. Predicted scatter plot
o Training vs. validation loss graph
• Provide a final comparison and discussion of how the deep learning model
performed compared to the Machine Learning models from Notebook 1.
💾 Optional but Encouraged
• Save your model using .h5 or .keras format
• Save your MinMaxScaler object using pickle
• Try tuning architecture (layers, neurons) and epochs
• Attempt regularization or dropout to reduce overfitting
