# Financial Planning with API

**Overview**
----
In this challenge, I have created two financial analysis tools in a single Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

**Requirements**
----
This project leverages python 3.7, APIs (Application Programming Interface) and SDK (Software Development Kits) to access current data.

Go to the homepage for Quandl at: https://www.quandl.com/ (This is where you will acquire the QUANDL API Key)

GO to the homepage for ALPACA API Keys at: https://app.alpaca.markets/signup (This is where you will acquire the ALPACA API Key and ALPACA SECRET KEY)

Once you acquire the API Keys, create and store the Keys in a .env file in Jupyter Lab with the following... QUANDL_API_KEY = “Your Quandl API Key Here” ALPACA_API_KEY = “Your ALPACA API Key Here” ALPACA_SECRET_KEY = “Your ALPACA Secret Key Here”

Go to your terminal or git bash and run conda activate dev to activate your conda dev environment. You will then install the following librarie(s) and module(s) to run in Python codes creatd.

conda install -c anaconda requests (Helps you access data via APIs) conda install -c jmcmurray json (Puts the response from an API into a human-readable format) pip install python-dotenv (Read key-value pairs from an environment file (.env) and add them as environment variables) pip install alpaca-trade-api (Alpaca is an API for stock trading. With the Alpaca SDK, you can interact with the Alpaca API)

**Instruction**
----
Go to the Anaconda Prompt to launch JupyterLab by typing Jupyter Lab. To use this application simply clone the repository and run the financial_planning_tools.ipynb in you Jupyter Lab Notebook.


