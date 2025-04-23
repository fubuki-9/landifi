

<!-- GETTING STARTED -->
# Features

* Borrowers can create their loan proposal with the amount they want, their favourable repayment due date and CID of their mortgage uploaded on IPFS.
> As of now we are using a decentralised public IPFS gateway. To use our DApp generate your file CID [here](https://www.dreamlink.cloud/) before adding it as a mortgage.
* Lender's can verify the borrower's data and send their proposal with their favourable interest rate.
* Borrower's can choose multiple lenders of their interest.
* Borrower can repay the loan anytime they want before the due date and amortized loan will be transacted.
* After the repayment date has passed, borrower cannot repay the loan and their mortgage will be revoked and auctioned off.

<div id="technologies-used" />

# Technologies, Libraries and Packages Used

1. Ethereum
2. Solidity
3. Truffle
4. MetaMask
5. JavaScript
6. Ganache
7. Web3
8. jQuery


<div id="local-setup" />

# Local Setup

> **Pre-Requisites**
> Ganache 
> MetaMask
> Truffle
1. Fork this repository.
2. Clone the repository
   ```sh
    git clone https://github.com/kshitij-404/DeFi-P2P-Lender.git
    ```
3. Open the folder in which you cloned the repository.
4. Open Ganache to run your local blockchain.
5. Run this command to build your smart contracts.
    ```sh
    truffle init
    truffle test
    truffle migrate --reset
    ```
6. Update your config.js present in frontend directory using abi and address present in build files.
7. Run on your local host and connect your wallet with metamask to perfrom the transactions.

