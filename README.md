# Ecommerce-Product-Categorization
In this project, the goal is to develop a multi-class text classifier for eCommerce product categorization. Accurate categorization of products is crucial for enhancing customer experiences, reducing search friction, and increasing product discoverability in the eCommerce domain. The approach involves analyzing a dataset containing product information, performing descriptive analysis and visualization to understand the data, building predictive models using machine learning techniques, and optimizing the models for maximum accuracy.

# Key Insights from Data Analysis and Visualizations:
# Descriptive Analysis:
Detailed examination of the dataset revealed 15,000 records with 15 features.
Missing values were identified and addressed, particularly in textual fields like 'description' and 'product_name'.
Summary statistics, distribution plots, and correlation matrices were used to understand numerical and categorical features.

# Text Data Analysis:
Textual data such as product names and descriptions were analyzed for length and content.
Word clouds were generated to visualize the most common words in product names and descriptions, providing insights into the textual content.

# Demonstration of the Predictive Model:
# Data Preprocessing:
Missing values were handled, and text data were preprocessed through normalization and TF-IDF vectorization.
The target variable was encoded for model training.

# Model Building:
Logistic Regression and Random Forest classifiers were trained on the preprocessed data.
Hyperparameter tuning using Grid Search was employed to optimize the Random Forest model.

# Model Evaluation:
The trained models were evaluated on test data using accuracy scores and classification reports.
The best-performing model was selected based on evaluation metrics.
Business Value Provided by the Solution:

# Improved Product Categorization:
The developed multi-class text classifier enhances the accuracy and efficiency of product categorization.
This leads to improved search experiences for customers, as products are accurately categorized and easier to find.

# Enhanced Customer Experience:
Accurate product categorization reduces search friction, allowing customers to quickly find relevant products.
Seamless product discovery contributes to a positive customer experience and increases customer satisfaction.

# Increased Sales and Revenue:
By improving product discoverability, the solution can potentially increase sales as customers find products more easily.
Enhanced customer experiences and efficient product categorization contribute to long-term customer loyalty and repeat purchases, ultimately driving revenue growth for the eCommerce platform.
Overall, the project aims to leverage data-driven approaches to enhance eCommerce product categorization, leading to improved customer experiences and business outcomes.
