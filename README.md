## 🐚 coquillage.eth

![homePage](https://user-images.githubusercontent.com/52472445/192144160-413ab3c1-d816-4c39-be3c-3a412d9bcb78.png)

## Live Demo
- ipfs://QmaSEQDjnsD1zpmGXdYNZxx74zgVr3A22sfCTaykfiXjgq
- https://coquillage-eth.surge.sh/
- https://coquillage.eth.limo/


## Getting Started with the developer environment

1) `git clone https://github.com/Bild96/coquillage.eth.git` to download the latest version

2) `yarn install` to install dependencies with yarn

3) [Create an Alchemy account](https://www.alchemy.com/) and put the key in [src/constants.js](./src/constants.js)

4) `yarn start` to run the developer environment

## Core files

* [src/index.js](./src/index.js) -> Boostraps React (enables [StrictMode](https://reactjs.org/docs/strict-mode.html)) and imports the main component from `src/App.jsx`

* [src/App.jsx](./src/App.jsx) -> Boostraps the examples homepage and setups the routing code for each example page found at `src/examples/`

* [src/examples/Balance.jsx](./src/examples/Balance.jsx) -> Example page for using the SDK to list balances of tokens from a wallet

* [src/examples/Vaults.jsx](./src/examples/Vaults.jsx) -> Example page for using the SDK to list Yearn Vaults and get detailed information from a single vault

* [src/examples/Deposit.jsx](./src/examples/Deposit.jsx) -> Example page for using the SDK to **deposit** a token at a Yearn Vault

* [src/examples/Withdraw.jsx](./src/examples/Withdraw.jsx) -> Example page for using the SDK to **withdraw** a token at a Yearn Vault

* [src/Home.jsx](./src/Home.jsx) -> Initial page loaded when no example is selected

* [src/styles.scss](./src/styles.scss) -> CSS file to create styling for components

* [public/index.html](./public/index.html) -> HTML file where React will inject the export from `src/index.js``

* [src/sdk.js](./src/sdk.js) -> SDK initialization code

* [src/wallet.js](./src/wallet.js) -> Browser Wallet connection initialization code

* [src/constants.js](./src/constants.js) -> API Keys and fixed addresses used

## More information
* **Yearn SDK Stack**: https://docs.yearn.finance/vaults/yearn-sdk/yearn-stack
* **Yearn SDK Repository**: https://github.com/yearn/yearn-sdk
* **Yearn SDK Documentation**: https://yearn.github.io/yearn-sdk/
* **Yearn API**: https://docs.yearn.finance/vaults/yearn-api
* **Yearn Protocol Documentation**: https://docs.yearn.finance/
* **Yearn Partner Documentation**: https://docs.yearn.finance/partners/introduction
* **What are Vaults and Strategies?**: https://medium.com/iearn/yearn-finance-explained-what-are-vaults-and-strategies-96970560432
