# finance
A web app that imitates managing portfolios of stocks for multiple users


Back-end (Python, Flask, SQLite):

1) allows user to register, log in and log out; 
2) passes current user’s portfolio of stocks data from the database to frontend; 
2) requests information about current stock price from AlphaVantage API, renders it to frontend; 
3) imitates “buy” and “sell” actions, updating database tables with new values; 
4) passes the history of the user’s transactions from the database to frontend. 

Front-end (JavaScript, jQuery, AJAX, Jinja): 

1) validates user’s login; 
2) renders current user’s portfolio of stocks using Jinja; 
3) renders information about a stock price using Jinja; 
4) renders history of a user’s transactions using Jinja.
