Monte Carlo Simulation for Stock Price Analysis
Overview

This project demonstrates how to use the Monte Carlo method to simulate stock price movements and evaluate investment outcomes. The example uses Microsoft (MSFT) stock data and forecasts possible investment results over a one-year period.
How It Works

    Data Retrieval: Historical stock data for MSFT is downloaded from Yahoo Finance, covering the period from January 1, 2020, to December 31, 2024.

    Annual Return Calculation: The mean annual return and standard deviation of stock returns are computed.

    Monte Carlo Simulation:

        Generates 1,000 potential price paths for MSFT over the next 365 trading days.

        Uses random variations based on historical return statistics to model stock price movements.

    Result Analysis:

        Simulated stock price paths are visualized.

        The final investment values are analyzed through a histogram.

Requirements

    Python 3.x

    Required Libraries:

        matplotlib

        numpy

        pandas

        yfinance

        datetime

Install dependencies using:
pip install matplotlib numpy pandas yfinance

Two key charts summarize the results:

    Stock Price Simulations: Displays multiple simulated price paths over a year.

    Investment Value Distribution: A histogram showing the final investment values across all simulations, highlighting risk and reward potential.
