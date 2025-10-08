# ADS-505 Final Team Project: Applied Data Science for Business

---

🍕 **Project Name:**
SliceWise: Pricing, Menu, and Ratings Analytics for U.S. Pizza Restaurants

---

**Data Source:**
Kaggle: Pizza Restaurants and the Pizza They Sell
[https://www.kaggle.com/datasets/datafiniti/pizza-restaurants-and-the-pizza-they-sell?resource=download](https://www.kaggle.com/datasets/datafiniti/pizza-restaurants-and-the-pizza-they-sell?resource=download)

---

💡 **Problem Statement:**
The Datafiniti dataset provides information on pizza restaurants in the United States. Information in this dataset includes restaurant names, locations, menu items, and prices. The goal of this analysis is to connect menu item type, pricing, and regional context to provide insights and recommendations on pricing strategies for pizza restaurant operators. Competitive pricing strategies can help pizza restaurants maximize revenue and attract more customers.

Predicting pizza prices by location, restaurant type, and menu items so companies can implement competitive pricing strategies.

---

📁 **Contents:**
This notebook covers the following key areas:

*   **Introduction:** Overview of the project and its objectives.
*   **Exploratory Data Analysis (EDA):** Data loading, initial inspection, handling missing values, outlier treatment, and visualizing feature distributions and relationships.
*   **Data Wrangling and Pre-Processing:** Feature engineering (e.g., date features, region, grouped city, pizza type, chain status), handling categorical variables, and splitting data for modeling.
*   **Modeling Strategy:** Regression modeling to predict exact prices and Classification modeling to predict price ranges, including the evaluation of various models (Linear Regression, Random Forest, Gradient Boosting, KNN, SVM, Neural Network).
*   **Validation and Testing:** Evaluating the performance of selected models on validation and test sets.
*   **Optimization Layer:** Applying model predictions to identify potentially underpriced/overpriced items and assessing price range alignment.
*   **Results:** Summarizing key findings and presenting pricing recommendations.
*   **Discussion and Conclusion:** Discussing the implications of the analysis and outlining future work.

---

🔍 **Project Highlights:**
*   Cleaned and preprocessed a dataset of U.S. pizza restaurant and menu data.
*   Engineered relevant features including location-based regions, simplified pizza types, and restaurant chain status.
*   Developed both regression and classification models to predict pizza prices and price ranges.
*   Identified Gradient Boosting and Random Forest as strong regression models and Neural Network, Decision Tree, and Random Forest as high-performing classification models.
*   Created an optimization layer to translate model predictions into actionable pricing recommendations, highlighting potentially underpriced/overpriced items and price range misalignments.
*   Provided specific examples of data-driven pricing recommendations.

---

📌 **Objective:**
To predict pizza prices by location, restaurant type, and menu items using the Datafiniti dataset, in order to provide U.S. pizza restaurant operators with data-driven insights and recommendations for implementing competitive pricing strategies.