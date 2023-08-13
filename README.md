# KryptoJobs2Go

![An image shows a wallet with bitcoin.](Images/19-4-challenge-image.png)


KryptoJobs2Go is an application where you can hire Fintech professionals using Ether as a form of payment. This project integrates Ethereum wallets and transactions into KryptoJobs2Go. The integration is accomplished using Python, the `web3` Python library, and the Streamlit library for a basic front end.

## Project Structure

This project consists of two Python scripts:

1. `crypto_wallet.py` - This file contains functions for generating an Ethereum account, retrieving the balance of an account, and sending transactions from one account to another.

2. `krypto_jobs.py` - This script serves as the main application. It utilizes Streamlit to create an interactive web application. You can select a candidate to hire, input the number of hours worked, and send a transaction to pay the candidate in Ether.

## Setup and Usage

To setup and run this project:

1. Ensure you have Python installed, preferably Python 3.7 or newer.

2. Clone this repository.

3. Install the required dependencies by running `pip install -r requirements.txt`.

4. Create a `.env` file with your environment variables, specifically your mnemonic seed phrase.

5. Start the Streamlit application by running `streamlit run krypto_jobs.py`.

6. Navigate to the local or network URL provided by Streamlit.

* KryptoJobs2Go Platform
Sign and Execute a Payment Transaction

<img width="600" alt="Ash 2 Example" src="https://github.com/kevgeedj/KryptoJobs2Go/assets/128102960/527a7ad9-2169-47f8-9e3c-c7d159249e69">

### Ganache Account

Here is a screenshot of the Ganache account showing the address, balance, and transaction (TX) count:

<img width="600" alt="Ganache Account Screenshot" src="https://github.com/kevgeedj/KryptoJobs2Go/assets/128102960/540eb5a9-5cdb-49f0-af11-1aaf0c8616a5">

### Ganache Transaction

Here is a screenshot of the transaction from the Ganache transactions tab:

<img width="600" alt="Ganache Transaction Screenshot" src="https://github.com/kevgeedj/KryptoJobs2Go/assets/128102960/cff35e76-a353-4fec-ae4e-a10f9483a9ce">
