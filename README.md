# financial-planner-app

This app has two financial analysis tools.
* A financial planner for emergencies. The tool can be used to visualize current savings and then determine if there is enough reserves for an emergency fund.

* A financial planner for retirement. This tool will forecast the performance of retirement portfolio in 30 years. This tool usus an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Technologies

This project uses python 3.9 with the following tools/libraries/APIs:

* [jupyter](https://jupyter.org/)

* [matplotlib](https://matplotlib.org/)

* [numpy](https://numpy.org/)

* [pandas](https://pandas.pydata.org/)

* [Alpaca API](https://alpaca.markets/docs/)

* [Monte Carlo Simulation](https://pbpython.com/monte-carlo.html)


---

## Usage

Signup for Alpaca account to get an API key to use. 
Create an environment file (.env) and store the following:
`ALPACA_API_KEY=<ALPACA API KEY>
ALPACA_SECRET_KEY=<ALPACA SECRET KEY>`

Open/Run `financial_planning_tools.ipynb` in jupyter notebook.

---

## Contributors

Contributed by Theena Dang (maria.cristina.dang@gmail.com)

---

## License

[MIT](LICENSE)


