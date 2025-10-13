# News Based Oil Price Predictor
This project predicts the price of oil based on news data.


## Project Structure
```md
/News_Based_Oil_Price_Predictor
│── lstm_xgboost_hybrid_attempt.ipynb        # Price prediction model based on LSTM and XGBoost hybrid
│── xgboost_hybrid.ipynb        # Price prediction model based on XGBoost
│── web_scraper.ipynb         # Get natural gas and oil news organized by date
├── news_sentiment_analysis.ipynb  # Calculate news based sentiments per day
├── daily_commodity_sentiment_gpu.csv  # News based sentiments stored per day
├── merged_boereport_output.csv  # Headlines stored per day
├── test-template.csv  # model test data
├── train_henry_hub_natural_gas_spot_price_daily.csv  # model train data
```


## Running Locally
Close repository: 
```bash
git clone https://github.com/19ndc2/News_Based_Oil_Price_Predictor.git
```

- run web_scrapper.ipynb to get news headlines
- run news_sentiment_analysis.ipynb to get news sentiments
- run xgboost_hybrid.ipynb to get price predictions
