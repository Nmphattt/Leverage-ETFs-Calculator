# ETF vs 3x Leveraged ETF Monte Carlo Simulation

This project is an Excel-based financial simulation model designed to compare the potential long-term portfolio outcomes of a standard ETF and a 3x leveraged ETF.

The model allows users to adjust key assumptions such as expected annual return, annual standard deviation, and initial investment amount. Based on these inputs, the spreadsheet converts annual assumptions into daily estimates and simulates portfolio value changes over 1,735 trading days.

Daily returns are generated using random z-scores to model price movement under a normal distribution assumption. The model then runs 5,000 Monte Carlo iterations for both the standard ETF and the 3x leveraged ETF.

The simulation outputs are used to calculate and compare:

- Mean final portfolio value
- Median final portfolio value
- Range of possible portfolio outcomes
- Probability that the standard ETF outperforms the leveraged ETF
- Impact of volatility and compounding on long-term performance

## Purpose

The main purpose of this project is to explore how leverage, volatility, and compounding interact over time. While leveraged ETFs may generate higher returns in strong upward markets, they can also experience volatility drag, especially during unstable or sideways market conditions.

This model is not intended to predict future market performance. Instead, it is designed as an educational tool to help users understand risk, uncertainty, and the distribution of possible investment outcomes under different assumptions.

## Key Features

- Adjustable annual return assumption
- Adjustable annual volatility assumption
- Adjustable initial investment amount
- Daily return simulation over 1,735 trading days
- Comparison between standard ETF and 3x leveraged ETF portfolios
- 5,000 Monte Carlo simulation iterations
- Mean and median portfolio value calculations
- Probability comparison between standard and leveraged ETF outcomes
- Built entirely in Microsoft Excel

## Assumptions

This model makes several simplifying assumptions:

- Daily returns are randomly generated based on a normal distribution
- Annual return and annual standard deviation are constant over the simulation period
- The leveraged ETF is modeled as 3x daily exposure
- Fees, taxes, transaction costs, tracking error, and borrowing costs are not included unless manually added
- Past or assumed return patterns do not guarantee future performance

## Educational Value

This project demonstrates concepts including:

- Monte Carlo simulation
- Portfolio risk analysis
- Volatility drag
- Compounding returns
- Leveraged ETF behavior
- Scenario analysis using Excel
- Investment outcome distribution analysis

## Disclaimer

This spreadsheet is for educational and research purposes only. It is not financial advice, investment advice, or a recommendation to buy or sell any financial product.

Users should conduct their own research and consult a qualified financial professional before making investment decisions.
