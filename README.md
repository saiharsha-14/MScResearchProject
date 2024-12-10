# MScResearchProject

This repository contains all the necessary components to replicate the project **"Enhancing Financial Forecasting through Transformer Models Using Social Media and News Insights"**.

## **Project Overview**
This project leverages the Temporal Fusion Transformer (TFT) and sentiment analysis to predict stock prices for Tesla (TSLA) and Apple (AAPL) using structured financial data and alternative sentiment data (Reddit and financial news).

## **Setup Instructions**
1. **Datasets**:
   - Preprocessed datasets and html files for web app  are stored in the `Stock_Web_UI` folder.
   - Sentiment analysis performed using FinBERT; processed data is included.

2. **Pretrained Models**:
   - Trained models (`tft_model_tsla.pth`, `tft_model_aapl.pth`) are located in the `models/` directory.

3. **Web Application**:
   - The interactive web app (`stock_web_UI.ipynb`) enables:
     - Real-time predictions.
     - Model comparisons (TFT vs. LSTM).
     - Trading strategy simulations.
   - Run the notebook in Jupyter/Colab for deployment.
     
4. **Results and Visualizations**:
   - Prediction plots, feature importance graphs, and trading strategy results are auto-generated in the app.
   - For detailed results, see the `results/` directory.

## **Workflow**:
1. Run `stock_web_UI.ipynb` to load datasets, models, and start the web application.
2. Access results and predictions through the web interface.
3. For a comprehensive understanding, refer to sections 7 and 8 of the project report.
