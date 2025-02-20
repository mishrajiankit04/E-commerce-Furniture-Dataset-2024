# E-commerce-Furniture-Dataset-2024
The project aimed to analyze and draw insights from the E-commerce Furniture Dataset 2024, which contains sales and product information of furniture items from AliExpress. The following steps were completed as part of the project:

1. Dataset Loading and Preprocessing:
* The dataset was loaded successfully, and any missing values in key columns (like originalPrice, price, and tagText) were handled appropriately.
* Data types were converted and cleaned for accurate analysis.

2. Exploratory Data Analysis (EDA):
* Identified the top 10 best-selling furniture products based on the number of units sold and visualized them using a bar chart.
* Analyzed the price distribution of the products to understand pricing trends in the dataset.* Gained insights into the impact of discounts by comparing originalPrice and price.

3. Predictive Modeling:
* A Linear Regression model was built to predict product prices based on features like the number of units sold (sold).
* The model was trained and tested successfully, providing valuable predictions and showcasing the relationship between sales and prices.

4. Insights and Findings:
* Products with higher discounts showed a noticeable increase in sales.
* Certain products (like those with "Free Shipping" tags) performed better, suggesting the importance of marketing strategies.
* The price distribution showed a mix of low-cost and high-cost furniture, catering to a diverse audience.

5. Challenges and Resolutions:
* Various errors (e.g., encoding issues, NaN values, and chained assignment warnings) were resolved during preprocessing and modeling.
* Adjustments were made to visualization code (e.g., fixing FutureWarnings in Seaborn) to ensure compatibility with future library versions.

Key Outcomes:
* The dataset provided valuable insights into consumer purchasing patterns and pricing strategies.
* A predictive model was successfully developed to estimate product prices, showcasing its potential for business decision-making.
