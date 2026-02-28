🏠 House Price Prediction Using Machine Learning
📌 Problem Statement

Predict house prices using structural property features such as bedrooms, bathrooms, living area, and year built.

📊 Dataset

Seattle housing dataset containing residential property details and sale prices.

⚙️ Features Used

Bedrooms

Bathrooms

Sqft Living

Floors

Condition

Year Built

🛠 Tools

Python

Pandas

Scikit-learn

Google Colab

🔎 Methodology

Removed zero price entries

Applied log transformation to normalize price distribution

Trained Linear Regression and Random Forest models

Evaluated using R² Score and RMSE

📈 Results

Linear Regression → R² = 0.44

Random Forest → R² = 0.43

Linear Regression slightly outperformed Random Forest for the selected features.
