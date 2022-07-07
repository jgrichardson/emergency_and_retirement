# Financial analysis for emergency and retirement funds

This application provides two financial planning tools:

1: A financial planner for emergencies. Users can visualize their current savings and determine if they have enough reserves for an emergency fund.

2: A financial planner for retirement. Users can forecast the performance of their retirement portfolio in 30 years. The application will make a call to the n Alpaca API via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

Information from the Monte Carlo simulations will answer questions about the user's portfolio.

## Technologies

* Python interpreter v3.9.12
* Pandas library: Data analysis and manipulation tools
* Matplotlib library: Creating static, animated, and interactive visualizations
* Python sys library: Support for system-specific parameters and functions
* Python requests library: for making REST API calls
* Python json library: for handling json data returned from API
* Python dotenv library: Support for using secure environment variables
* Python alpaca_trades_api library: for interacting with Alpaca API
* Python MCForecastTools library: for conducting data simulations

## Usage
To use this emergency and retirement financial planning application simply clone the repository and open the financial_planning_tools.ipynb script in the Jupyter Lab application.

```financial_planning_tools.ipynb```

## License

The source code for the application is licensed under the MIT license, which you can find in the LICENSE file in this repo.