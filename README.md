# ds_-Ankur_Saini-

 Trading Performance vs. Market Sentiment – Analysis Report

This repository contains a complete analysis of how trading behavior and profitability vary across different market sentiment conditions (Fear, Greed, Extreme phases). The study combines a historical trading dataset with the Fear & Greed Index to uncover performance patterns, trader behavior, and risk levels.

 Project Overview

The goal of this project is to analyze how trader outcomes change as market sentiment shifts.
Using a merged dataset of trade records and sentiment labels, the notebook explores:

Trade volume behavior

Profitability trends

Win rates

PnL volatility (risk)

Positioning patterns

Overall trader performance across sentiment categories

The results highlight how market psychology influences trading outcomes.

 Repository Contents
File	Description
ds_task.ipynb	Jupyter Notebook containing full data loading, preprocessing, analysis, and visualizations.
report.docx (optional)	Detailed written report summarizing all analysis steps and insights.
README.md	Project overview, instructions, and documentation.
 Key Insights from the Analysis
1. Trading Activity

Traders were most active during Fear sentiment periods.

Trade volumes were lowest during Extreme Fear.

Average trade size was largest in Fear and smallest in Extreme Greed.

2. Profitability

Average profit per trade was highest in Extreme Greed.

Neutral and Extreme Fear phases produced the lowest average PnL.

3. Win Rate

Extreme Greed had the highest win rate (~46%).

Extreme Fear had the lowest (~37%).

4. Risk (PnL Volatility)

Risk (standard deviation of PnL) was highest during Extreme Fear and Greed.

Neutral days were the most stable and least volatile.

5. Trader Positioning

Traders often opened large short positions during Greed.

They opened large long positions during Extreme Greed.

Fear and Extreme Fear positions were smaller and mixed.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook
Contributions, improvements, and suggestions are always welcome.
Feel free to open an issue or submit a pull request.
