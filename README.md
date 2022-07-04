# Fintech-Finder-Application : Ethereum Transaction Functions

## Challenge19

# Description

Working at a stratup that is building a new and disruptive platform called "Fintech Finder". Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I have assigned tasked with integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency. 

To complete this challenge, I will assume the perspective of a Fintech Finder customer in order to do the following:

- Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

- Fetch and display the account balance associated with your Ethereum account address.

- Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

- Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

- Review the transaction hash code associated with the validated blockchain transaction.

- Once receive the transaction’s hash code, I will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that I have successfully created the transaction, I need to save screenshots to the README.md file of my GitHub repository for this Challenge assignment.

# Instructions 

The steps for this challenge are broken out into the following sections:

Step 1 - Import Ethereum Transaction Functions into the Fintech Finder Application.

Step 2 - Sign and execute a pyament transaction

Step 3 - Inspect the transaction on Ganache

# Inspect the transaction

The following screenshots demonstrates the Home Applicagtion Page, as well as a completed transacton verified in Ganache.

In the following application example, the user selected "Lane" for 100 hours. Lane's hourly rate is 0.2 Ether/hour. So the wage due in Ether is 20.0.
After confriming the details, Click the "Send Transaction" button to sign and send the transaction with Ethereum account information. Navigate to the Transactions section of Ganache.
The transaction can be confrimed by viewing Below Validated Transaction .

# Verified in Ganache Fintech Finder Web App Screenshot
![alt text](https://github.com/)










To confirm this transaction was completed, we can view our account details in Ganache to review our address, balance, and transaction (TX) count. We know that this account started with 100 Ether, and the following screenshot indicates that 20 Ether was sent, leaving us with a current balance of 80 Ether.

# Screenshot
[alt text](https://github.com/)










To review the transaction details, navigate to the Ganache Transaction tab where the details can be view below:

# Screenshot
[alt text](https://github.com/)










# Technologies

This project leverages Python 3.7. The following packages are also used:

- Streamlit - Tool to build user friendly, web based data apps in Python

- Web3.py - Python library for connecting and performing operations on Ethereum-based blockchains.

- ethereum-tester - Python library to provide access to the tools to test Etherum-based applications.

_ Ganache - Program that allows for quickly seeting up a local blockchain to use to test and develop blockchain based apps


# Installation Guide

Before running the application, install Python modules streamlit, web3 and ethereum-tester:

- pip install streamlit

- pip install web3==5.17

- pip install eth-tester==0.5.0b3

