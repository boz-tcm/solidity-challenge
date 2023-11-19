<img src="Resources/Images/photo-1694903110330-cc64b7e1d21d.png" align="right"/>

# `Columbia Engineering FinTech Bootcamp 2023-06 Cohort`

## `Project: Module 20 Solidity-Challenge`

## Background
> We have recently been hired by a fintech startup company that is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain connecting financial institutions.

## Purpose
> The team currently is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts. To automate the creation of joint savings accounts, we'll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Our smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Table of Contents
* [Background](#background)
* [Purpose](#purpose)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->

## Technologies Used
- Python Version 3.10.13
- Remix IDE 0.37.3 via Chrome Web Browser
- Pragma Solidity >= 0.5.5 (requires compiler 0.5.5 or greater, and less than 0.6.0)
- VS Code IDE 1.84.2
- Chrome 119.0.6045.123 (Official Build) (arm64)
- Markdown

## Screenshots

### `Screenshots below depict Streamlit and Ganache application and transaction audit trails for sending Ether to selected Fintech independent contractor, Kendall, at the hourly rate of 0.16 ether, for two hours of contracted work:`

#### `1. Customer's Accounts Tab in Ganache Prior to Sending Transaction to Fintech Independent Contractor:`
![A screenshot depicts customer's ganache accounts tab prior to sending transaction.](Resources/Images/1.%20Ganache%20Prior%20to%20Sending%20Transaction.png)

#### `2. Customer's Streamlit App Page Following Execution and Blockchain Validation of Sending Transaction to Fintech Independent Contractor, includes validation and transaction hash, along with Customer's Ethereum address (base address, or index 0) and selected independent contractor's Ethereum address:`
![A screenshot depicts customer's streamlit following validated transaction send.](Resources/Images/2.%20Streamlit%20After%20Successfully%20Sending%20Transaction.png)

#### `3. Customer's Accounts Tab in Ganache After Sending Transaction to Fintech Independent Contractor, reflects reduction in customer's base account ether:`
![A screenshot depicts customer's ganache accounts tab following validated transaction send.](Resources/Images/3.%20Ganache%20After%20Successfully%20Sending%20Transaction.png)

#### `4. Customer's Transactions Tab in Ganache Showing Validated Transaction Send to Fintech Independent Contractor, including to: and from: Ethereum addresses, transaction hash reflecting validation, along with ether transmitted (in wei) and gas used (in wei) to validate:`
![A screenshot depicts customer's ganache transactions tab following validated transaction send.](Resources/Images/4.%20Ganache%20Transaction%20Log%20After%20Successfully%20Sending%20Transaction%20to%20Kendall.png)

#### `5. Customer's Transactions Tab Detailed in Ganache Showing Validated Transaction Send to Fintech Independent Contractor, including to: and from: Ethereum addresses, transaction hash reflecting validation, gas price (in wei), account block mined, along with ether transmitted and gas used (in wei) to validate:`
![A screenshot depicts customer's ganache transactions tab following validated transaction send.](Resources/Images/5.%20Ganache%20Transaction%20Log%20After%20Successfully%20Sending%20Transaction%20to%20Kendall%20(addtl%20detail).png)

## Setup
- GitHub Repository
    - name: 'blockchain-wallets-challenge'
    - location: uploaded to Bootcamp homework submission online portal and available publicly at:
        - [GitHub Repository](https://github.com/boz-tcm/blockchain-wallets-challenge.git)
- Python Standard Library Version 3.10.13
- Python Libraries and Modules:
    - crypto_wallet and generate_account, get_balance, send_transaction
    - dataclasses and dataclass
    - streamlit 1.27.2
    - typing and Any, List
    - web3 Version 5.17 and Web3 

- Python File(s):
    - [Project's main code file `'fintech_finder_krypto_jobs.py'`](fintech_finder_krypto_jobs.py)
    - [Ethereum base support functions file `'crypto_wallet.py'`](crypto_wallet.py)    
- Data:
    - [Send Transaction Cost.xlsx](Resources/Data)
- Images:
    - location: [README Screenshot Images](Resources/Images)
    - location: [Streamlit Application Images](Images)
- README:
    - location: [README.md](README.md)

## Usage
The scripts are run in the project's Python files cited in [Setup](#setup), located within the project's GitHub repository root directory, and executed via Streamlit in a VS Code terminal using the command `'streamlit run fintech_finder_krypto_jobs.py'`.

## Project Status
Project is: _complete

## Room for Improvement
Room for improvement: _

To do: _

## Acknowledgements

## Contact
Created by Todd C. Meier, tmeier@bozcompany.com - feel free to contact me!

<!-- ## License --> All rights reserved.