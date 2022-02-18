![ETF analyser](Images/ETF_analyser.png)

# ETF_analyser_app
Web application using SQL, Python and the Voilà library to analyze the performance of an ETF.

The main features of this application are:

* **Analyze a single asset in the ETF**
![Paypal Daily returns](Images/pypl_returns.png)

* **Optimize data access with Advanced SQL queries** 
  *  Accessing the closing prices for PYPL that are greater than 200, and 
  * Finding the top 10 daily returns for PYPL


* **Analyze the ETF portfolio**
![ETF Cumulative returns](Images/ETF_cumureturns.png)

* **Deploy the notebook as a web application**


https://user-images.githubusercontent.com/94496049/154753103-e7f61ec3-44de-4ff1-b35f-6ca44540bd78.mov



## Tecnologies required and installation guide:

* **SQL Alchemy**

``` pip install SQLAlchemy```

* **Voilà**

``` conda install -c conda-forge voila ```

## Instructions

Use the `etf_analyzer.ipynb` notebook to visualize and analyze the performance of any ETF.

Note that this application requires the use of hvPlot for the visualizations.

## Contributors

Jaime Aranda


---

## License

Licensed under the MIT License.
