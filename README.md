## <h1><b>Stock Price Forecasting</b></h1>

## <h3>Overview:</h3>
<p>
Examining stock market data is both intriguing and potentially lucrative, especially when strong predictive models can lead to significant financial rewards. Although the web is saturated with financial information, finding a well-structured dataset that captures essential stock metrics across various companies can be a challenge.

In this project, we will focus on a New York Stock Exchange dataset from Kaggle (https://www.kaggle.com/datasets/dgawlik/nyse/data), which includes critical stock price information—Open, Close, High, Low—alongside the date, symbol, and trading volume. Spanning from 2010 to the end of 2016, this dataset provides a solid foundation for our analysis.

Our goal is to explore these key metrics to identify patterns and trends that can inform our predictive models. By applying advanced analytical techniques, we aim to enhance our understanding of stock price movements and uncover actionable insights that could lead to financial success. Join us as we navigate the world of stock price prediction and leverage data-driven strategies for informed investment decisions.
</p>

## <h3>Repo Structure</h3>
* The stock_price_forecasting.ipynb file contains python code related to this application.
* The data folder has prices.csv file that contains sample data used in this application.

## <h3>Business Objective</h3>
<p>
To effectively forecast future stock price movements, our project aims to develop a predictive model that leverages historical data and relevant market indicators. The following objectives will guide our analysis:

Develop a Predictive Model: Create a robust predictive model that accurately forecasts future stock price movements using historical data and relevant market indicators.

Identify Key Factors: Analyze and identify the key factors and market indicators that significantly influence stock price movements, ensuring the model incorporates these variables.

Enhance Prediction Accuracy: Achieve a prediction accuracy of at least X% (define a specific percentage based on your goals) using metrics such as Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE).

Evaluate Techniques: Explore various modeling techniques (e.g., ARIMA, LSTM, regression analysis) to determine the most effective approach for stock price prediction.

Provide Actionable Insights: Deliver actionable insights to stakeholders based on model predictions, enabling informed investment decisions and strategy development.

Continuous Improvement: Establish a framework for ongoing model evaluation and refinement to adapt to changing market conditions and improve prediction performance over time.
</p>

## <h3>CRISP - DM Framework</h3>
<p>
 The Cross-Industry Standard Process for Data Mining (CRISP-DM) is a widely recognized framework that facilitates successful data science initiatives. This structured approach encompasses the following key phases:

Business Understanding: Define project objectives and requirements from a business perspective, identifying key stakeholders and their needs.

Data Understanding: Collect initial data and explore its characteristics, identifying data quality issues and assessing relevance.

Data Preparation: Clean and preprocess the data to ensure quality and consistency, transforming it into a suitable format for analysis.

Modeling: Select appropriate modeling techniques based on the problem and data characteristics, building and training models using the prepared data.

Evaluation: Assess the model's performance against established success criteria, reviewing the process to ensure all objectives have been met.

Deployment: Implement the model in a production environment, monitoring its performance over time and communicating results to stakeholders.

In this project, we will leverage the CRISP-DM framework to guide our analysis and ensure a systematic progression through each phase. By doing so, we aim to enhance our insights and achieve our objectives more effectively. 
</p>

## Key Highlights
*   **Model Selection**: Evaluated and selected ARIMA, SARIMA, and Prophet models based on their suitability for capturing trends, seasonality, and irregular patterns in stock price data.
*   **Parameter Optimization**: Conducted hyperparameter tuning for ARIMA and SARIMA models using techniques like grid search, leading to improved forecasting accuracy.
*   **Seasonality Detection**: Identified seasonal patterns in stock prices through SARIMA, demonstrating the model's ability to account for periodic fluctuations.
*   **Forecast Horizon**: Generated forecasts over various time horizons (short-term vs. long-term), providing valuable insights for different investment strategies.
*   **Residual Analysis**: Performed residual analysis to check for autocorrelation and normality, ensuring that model assumptions were satisfied and enhancing the reliability of forecasts.
*   **Prophet's Flexibility**: Leveraged Prophet's ability to incorporate holiday effects and custom seasonality, leading to improved forecasts during critical market events.
*   **Error Metrics Interpretation**: Analyzed MSE, RMSE, and R² scores to quantify model performance, providing a clear understanding of prediction accuracy and model reliability.
*   **Impact of External Factors**: Explored the influence of external factors (e.g., economic indicators, market sentiment) on stock price movements, enhancing the context of your forecasts.
*   **Actionable Insights**: Delivered actionable insights based on forecast results, aiding stakeholders in making informed investment decisions and risk management strategies.
*   **Best Model**: LSTM is best performing model among all four models.

## Next Steps and Recommendations
*   Conduct further validation of the models using additional datasets to ensure robustness and generalizability of the forecasts.
*   Explore advanced techniques such as ensemble methods to combine predictions from multiple models for improved accuracy.
*   Develop a dashboard for visualizing forecasts, actual prices, and error metrics, providing stakeholders with an interactive tool for decision-making.
*   Plan for regular updates of the machine learning models with new data to maintain accuracy and relevance in a dynamic market environment.
*   Investigate the integration of deep learning algorithms (e.g., LSTM, GRU, CNN etc.) to enhance forecasting capabilities and capture complex patterns in the data.
*   Document the entire machine learning modeling process, including methodologies, parameter choices, and insights gained, facilitating knowledge sharing and future reference.
*   Plan for regular updates of the machine learning models with new data to maintain accuracy and relevance in a dynamic market environment.
