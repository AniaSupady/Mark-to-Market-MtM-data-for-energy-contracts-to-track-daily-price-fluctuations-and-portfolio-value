# Mark-to-Market-MtM-data-for-energy-contracts-to-track-daily-price-fluctuations-and-portfolio-value
This repository contains Python code to simulate Mark to Market (MtM) data for energy contracts, including oil, gas, and renewables. It models daily price fluctuations and calculates the portfolio value over time, providing insights into the real-time market value of assets or contracts.

https://github.com/AniaSupady/Mark-to-Market-MtM-data-for-energy-contracts-to-track-daily-price-fluctuations-and-portfolio-value/blob/main/Mark_to_Market_(MtM).ipynb


# Explanation of the Code

## Simulated Prices:
- I simulated daily prices for oil, gas, and a renewable energy index using a random walk with a slight trend.
- Oil prices start at $70/barrel, gas prices at $3/MMBtu, and renewables at $50.

## Portfolio Positions:
- The portfolio includes long positions in oil and gas and a short position in renewables.
- Positions represent quantities held (e.g., barrels of oil or MMBtu of gas).

## Mark to Market (MtM) Calculation:
- The MtM value for each commodity is calculated as `price * position`.
- The total portfolio MtM is the sum of the individual MtMs.

## Visualization:
- The plot shows the MtM values for each commodity and the total portfolio over time.

## Output Data:
- The first few rows of the simulated dataset are printed for reference.
