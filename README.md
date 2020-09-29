# StarNotary DAPP

### Important Notes:
* I wasn't able to get Eth from faucets for Rinkeby Test Network from the 2 websites provided in the course, I also wasn't able to find other faucets, so as a result, **I deployed my token's contract on the Ropsten Test Network** instead.
* I used my own Metamask seed when I deployed the token's contract, however, I removed it before putting my code on GitHub, since as we were taught throughout the course, the seed must be kept secret, I also removed my infura key, so in case you want to deploy my code on the Ropsten Test Network to check that it works properly, **make sure to put your Metamask seed and infura key (in the truffle-config.js file)**.
* In case you also want to deploy my contract on the Ropsten Test Network, you might need to change the **gas limit** in the **truffle-config.js** file, as it keeps changing (go to Etherscan, check the gas limit of the last block added to the Ropsten Test Network, and put a value that is smaller than the value shown in a bit).

### Project Requirements:
* OpenZeppelin Version: 2.1.2
* Truffle Version: v5.1.45 (core: 5.1.45) 
* Token Name: Mira
* Token Symbol: AMN
* Token Contract Address on **Ropsten Test Network**: 0x0c7328597bc6fb5ac641e36cc308e92c7307c2de

### Additional Information:
* Solidity: v0.5.16 (solc-js)
* Node: v12.18.3
* Web3.js: v1.2.1

