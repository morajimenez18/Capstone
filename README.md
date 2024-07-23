# Capstone
Capstone
## SpaceX Launch Data Analysis and Prediction

This repository contains code and data used for a comprehensive analysis of SpaceX Falcon 9 launch data, aiming to predict the success of first-stage landings. The project leverages various tools and techniques, including:

**Data Collection:**

- Web scraping from Wikipedia to gather initial launch data.
- Utilizing the SpaceX API to supplement data with additional information like payload mass and booster flight numbers.

**Data Wrangling:**

- Cleaning and preparing the data by removing inconsistencies and missing values.
- Transforming the data to ensure consistent scaling and prepare it for machine learning.

**Exploratory Data Analysis (EDA):**

- Visualizing data trends and relationships using Pandas, Matplotlib, and Seaborn.
- Identifying key patterns and insights from the data through various visualizations.

**Interactive Visual Analytics:**

- Building an interactive dashboard with Plotly Dash for exploring data relationships.
- Enabling users to filter and visualize data by launch site, payload mass, and other variables.

**Predictive Analysis:**

- Training and evaluating machine learning models (Logistic Regression, SVM, Decision Trees, KNN) to predict landing success.
- Optimizing model performance through hyperparameter tuning using GridSearchCV.

**Key Findings:**

- **Launch Site Impact:** Specific launch sites like KSC LC-39A demonstrate significantly higher success rates.
- **Payload Mass Correlation:** A strong inverse relationship exists between payload mass and successful landings.
- **Model Performance:** The K-Nearest Neighbors (KNN) model achieved the best performance in predicting landing success, reaching an accuracy of 83.33%.

**Project Structure:**

- **Data:** Raw and processed data files.
- **Code:** Scripts for data collection, wrangling, EDA, visualization, and model training.
- **Dashboard:** The Plotly Dash dashboard code and associated files.
- **Presentation:** The accompanying presentation summarizing the project findings and insights.

**How to Use:**

- **Data Exploration:** Utilize the interactive dashboard to explore relationships between launch site, payload mass, booster version, and landing outcomes.
- **Model Prediction:**  Apply the trained KNN model to predict landing success for new launch scenarios.

**Contributions:**

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements.

**Disclaimer:** This project is for educational and research purposes only.
