# Bike Sharing Demand Prediction

**Objective**

The objective of this project is to develop a multiple linear regression model to predict the demand for shared bikes based on various influencing factors. This will help the bike-sharing company, BoomBikes to understand demand dynamics and refine their business strategy post-COVID-19 lockdowns.

**Problem Statement**

BoomBikes, a US-based bike-sharing service, experienced a significant decline in revenue during the COVID-19 pandemic. To recover and sustain in the competitive market, the company aims to predict demand for shared bikes after the lockdowns end. By understanding the key factors that influence demand, BoomBikes plans to align its strategies to better cater to customer needs, expand into new markets, and achieve significant revenue growth.

**Approach**

1. Data Exploration and Preparation:
    * Conducted an initial inspection of the dataset.
    * Converted ordinal categorical variables into appropriate categorical formats for accurate analysis.
    * Retained important variables such as yr (year) due to its significance in predicting demand growth trends.
2. Feature Selection:
    * Focused on relevant variables like temperature, season, weather conditions, and others that significantly affect bike-sharing demand.
3. Model Building:
    * Used cnt (total rentals) as the target variable, which combines casual and registered user counts.
    * Built a **Multiple Linear Regression Model** to identify the most significant predictors and their impact on demand.
4. Model Evaluation:
    * Assessed model performance using metrics like R-squared on both training and test datasets.
    * Conducted residual analysis to ensure the model's assumptions were met.

**Key Insights**

* Temperature: The most significant predictor, with demand increasing by approximately 47% for every 1-degree rise in temperature.
* Annual Growth: A positive coefficient for the year (yr) indicates an expected 23% annual growth in bike rentals.
* Seasonality: Winter and September show positive impacts on demand, while spring and summer exhibit a decline due to weather conditions.
* Weather Impact: Negative coefficients for conditions like "Mist + Cloudy" and "Light Snow + Light Rain" highlight reduced demand during adverse weather.
* Baseline Growth: The intercept term suggests a baseline business growth of 19% even without specific influencing factors.

**Recommendations**

* Focus marketing efforts during high-demand periods such as winter and September.
* Develop strategies to mitigate the impact of adverse weather conditions on demand.
* Utilize temperature trends to forecast demand and adjust operational capacities accordingly.
* Leverage the 23% annual growth potential by expanding operations and targeting new customer bases.

This analysis equips BoomBikes with actionable insights to optimize their business model and address customer needs effectively. The predictive model provides a robust foundation for strategic decision-making and market expansion.
