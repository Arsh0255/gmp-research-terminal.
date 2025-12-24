Disclaimer

This project is for academic and research purposes only and does not constitute investment advice.


# Global Monetary Policy Impact (GMP) Research Terminal

An interactive research terminal designed to analyze and simulate the impact of 
central bank monetary policy decisions on financial markets using machine 
learning, event studies, and NLP.

## Overview
This project studies how policy decisions by the Federal Reserve (FOMC) and the 
Bank of England (BoE) affect equity markets and bond yields. It integrates 
macroeconomic indicators, policy text sentiment, and market reactions into a 
unified analytical framework.

## Key Features
- Event Study analysis using Cumulative Abnormal Returns (CAR)
- NLP-based sentiment extraction from central bank policy statements
- Random Forest models for market reaction prediction
- Stress-testing and scenario simulation framework
- Interactive Streamlit dashboard with 2D & 3D visualizations

## Data Sources
- Federal Reserve Economic Data (FRED)
- FOMC policy statements (2010–present)
- Bank of England policy rate data
- FTSE 100 market data (Yahoo Finance)

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest)
- NLP (policy sentiment analysis)
- Streamlit & Plotly
- Time-series and macroeconomic analysis

## How to Run
```bash
pip install -r requirements.txt
streamlit run app/gmp_global_app.py
