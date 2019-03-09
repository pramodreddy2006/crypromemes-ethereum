# cryptomemes
Buy Memes on the Blockchain. 
- [Beta website](http://cryptomemes.lol/)
- [Ethereum contract](https://etherscan.io/address/0x0d623823d2aa4540f335bb926447dc582dc5bd64)

## How it works
- Contract is deployed at ethereum and tokens for memes are created on blockchain.
- Stores all the memes in mysql database. Scripts present at **db-scripts**
- cron job present at **db-cron** gets the transactions from **etherscan** api and updates the database.

## Local running instructions
- run the command - npm install in root directory
- execute truffle-build.sh
- run the command -  node server.js