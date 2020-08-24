# js-trading-algo
Simple stock trading algorithm that is built with Alpaca API. There is also an interactive browser version.

### algo.js
* This is a simple algorithm that incorporates daily rebalancing to limit volatility and increase returns 
    * Set up so you can edit your holdings and weights however you like
* Environment Variable Setup
    * Create a .env file with your api credentials
        * APCA_API_KEY_ID=apiKey
        * APCA_API_SECRET_KEY=secretKey
        * APCA_API_BASE_URL=https://paper-api.alpaca.markets
    * Create a package.json file
        * 'npm init -y' in your terminal will do this for you, be sure to cd to the same directory as your .env file
    * Install the dotenv npm package
        * npm install dotenv
        
### Rebalance-Browser
* First need to download the folder from my github.. 
* Run the HTML file within a browser, I use Chrome. 
* Plug in your Alpaca Key ID and your Alpaca Secret Key ID
* Click on run and it will instantly run Rebalance Algorithm within your account
    * Must be a paper account unless you tweak some code.
* The script will output some logs as well as your positions open and the orders placed

### Long-Short-Browser
* [alpaca js github](https://github.com/alpacahq/alpaca-trade-api-js/tree/master/examples/long-short-browser)
