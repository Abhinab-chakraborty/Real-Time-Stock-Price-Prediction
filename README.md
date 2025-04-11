# Real-Time Stock Market Price Visualizer
A robust system to analyze real-time stock market data for effective price movement prediction and visualization.

# Overview
This project implements a comprehensive stock market data pipeline that tracks and analyzes five major technology stocks (AAPL, GOOGL, MSFT, AMZN, TSLA). The system incorporates real-time data acquisition, streaming processing, and persistent storage, enabling comprehensive market analysis and monitoring through interactive dashboards.

# Features
* Real-Time Monitoring: Continuous data stream from Yahoo Finance ensuring uninterrupted market surveillance
* Data Analysis: Historical price tracking, volume analysis, price correlation studies, volatility measurements
* Interactive Visualization: Apache Superset dashboards for monitoring stock performance
* Efficient Storage: PostgreSQL database optimized for time-series financial data
* Streaming Architecture: Apache Kafka for reliable data streaming and processing

# Data Acquisition
* Data Source: Yahoo Finance API (via yfinance Python package)
* Update Frequency: Real-time market data with 1-minute intervals
* Stocks Tracked: Apple (AAPL), Google (GOOGL), Microsoft (MSFT), Amazon (AMZN), Tesla (TSLA)

# Data Processing
* Streaming Platform: Apache Kafka
* Topic Structure: "stock-prices" topic for all stock data
* Processing Framework: Python-based data handling system for validation and transformation

# Data Storage
* Database System: PostgreSQL
* Database Name: "stock"
* Table Structure:
    * Individual tables for each stock: AAPL, GOOGL, MSFT, AMZN, TSLA
    * Schema per table: symbol, price, volume, timestamp


# Visualization

* Dashboard Tool: Apache Superset
* Chart Types: Line charts, bar charts, time series analysis, correlation matrices

# Installation & Setup
 # Prerequisites

* Python 3.7+
* Apache Kafka
* PostgreSQL
* Apache Superset

# Python Dependencies
* kafka-python
* yfinance
* psycopg2
* psycopg2-binary

# Dashboard
Access the Superset dashboard to visualize stock data and analytics.

# Applications and Benefits
    # Trading Insights

* Real-time market monitoring for immediate visibility into market movements
* Technical analysis support with various indicators and chart patterns
* Trading pattern identification using advanced algorithms
* Risk assessment capabilities to manage market exposure

    # Portfolio Management

* Multi-stock tracking for monitoring multiple positions simultaneously
* Performance comparison capabilities for benchmarking holdings
* Correlation analysis to understand relationships between different stocks
* Risk diversification insights for optimized asset allocation
