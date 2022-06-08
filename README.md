# nft.sol.marketplace
###
- local network
```
# prerequisites
$ npm install
$ npm install -g truffle

# contract(compile, test, deploy on local network)
$ truffle compile
$ truffle test
$ truffle migrate

# run
$ npm start
```
- public network
```
# .env setting
PRIVATE_KEYS: Private Key of the account you are using to deploy (typically the first one in the list of Ganache)
INFURA_API_KEY: API key provided by Infura: https://infura.io

$ truffle migrate --network ropsten
$ npm run build
```
