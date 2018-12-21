'The Emperor' is an online stock-trading simulation that aims to build upon and extend beyond the p-set 8 project "Finance".
In this platform, users are able to buy and sell stocks with the virtual currency available to them at the start of the game ($10,000 by default), and see the performace of their chosen stocks on their portfolio.

When the server loads, the user is automatically redirected to the homepage where they are asked to either log in or sign up. For log in and sign up forms to appear, the user needs to press the respective buttons on the screen.
If the user decides to log in, he/she simply inputs the password and username in the "Log in" form.
If the user decides to sign up, he/she needs to fill the "Sign Up" form to create a new username and password. The password has to include at least one lowercase, uppercase, numeric, and special character.
If the requirement is not satisfied, the "Register" button is automatically disabled, and user is alerted with a message. The password and password confirmation tabs also need to match; else, the tabs would assume a red border and the user will see a message at the bottom of the form.

After the user logs in or signs up, he/she is directed into the "Stock Search" page. In this page, the user can see a list of "Most Gainer" and "Most Loser" stocks, which are expected to guide the user in his/her stock search. Each gainer/loser stock include a link embedded into its symbol name in the first column and a percent change column showing its recent performance.
Another thing to note is that as soon as the page loads, the search bar at the top-right corner opens for user to input a stock name. When the user enters a stock symbol in this search bar and clicks "Enter/Return" on the keyboard, he/she is automatically directed to the "Stock Information" page with information relevant to that stock. The search tab has been designed to be case- and space-insensitive.

In the "Stock Information" webpage, the user is supplied  with relevant financial information about the stock. The price of the stock is updated every 5 seconds with the server. The stock change symbols are colored either red or green based on the stock's recent movement (up or down). The page also includes links to the company's page and NASDAQ financial statements.
The page also includes an interactive graph showing the stock's performance over the given time intervals. The user is able to select the time interval through the buttons on top or the slider on the bottom and the graph will adjust accordingly.
The user is also able to buy or sell that stock through the "Buy","Sell", and "Shares" column. Buy and sell buttons are disabled until the user inputs a valid amount of share.

After making a purchase, the user is redirected inot the protfolio page, where he/she sees the company stocks owned and their percent return. This give the user an idea of how the purchased stocks have been performing recently. The user also has the ability to buy/sell stock right from the Portfolio page without going back. Please note that the Portfolio page may take a while to load based on the number of stocks owned by the user. This is due to the heavy nature of the Python function that calculates the relevant informationa and sends it to the html server.
If the user sells all his/her shares of a stock thorugh the portfolio webpage, the stock disappears from the list automatically. If the user tries to sell more than he/she owns, he/she is rediected to the apology webpage which says "Too Many Shares."

There is also password change function which enables the user to update their password. The user also can transfer money to another user through the 'transfer' page. Both these pages have been optimized against the user errors.

The app is designed for mostly desktop use. The graphics may be not suitable for smaller screens.