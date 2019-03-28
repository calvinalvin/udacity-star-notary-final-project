### Udacity Star Notary Final Project

- ERC721 Token Name: `Calvin's Star Notary`
- ERC721 Token Symbol: `STR`
- Token Contract Address on Rinkeby: `0xca9B3970f943C837DA19b5301e3C1f26574bb798`

#### Instructions on running project locally

- First you must have a truffle development environment running. If you haven't installed truffle yet then `npm install truffle -g`
- Start truffle `truffle develop`. This will spin up a local blockchain.
- Compile the StarNotary contract with `compile` while in truffle console.
- Run the tests by running `test` while in the truffle console.
- Migrate the StarNotary contract onto the blockchain by running `migrate --reset`. The `--reset` flag makes sure that the migrations are run from the beginning.
- Start the web app by going into the `/app` folder. While in the `/app` run the command `npm run dev` which will start the webpack development server which will start the webpack development server. This will deploy a website at `http://localhost:8080`. 


#### Version Information

```
Truffle v5.0.7 (core: 5.0.7)
Solidity - 0.5.2 (solc-js)
Node v8.11.0
````

