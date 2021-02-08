# ContractCrawler
Crawler that gets verified contracts from etherscan.io.

**WHAT YOU NEED**
- .csv file containing the address of the contracts.Just place it in the same folder as main.py. I got mine by querying [this](https://github.com/blockchain-etl/ethereum2-etl) database.
- API key from etherscan.io. (optional)


**TO RUN THE CRAWLER**
1. Enter the name of you .csv file.
2. Select an extension for your destination files(sol or txt).
3. Select the simple scraper or the API option: in the first case the crawler will start immediately, otherwise you'll be required to enter the API key, in order to be able to get the smart contracts.