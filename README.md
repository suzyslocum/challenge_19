# Create a Blockchain Based Ledger System & Web Interface

*Module 19 Challenge Assignment *

---

## Overview 
---
  We have created a web application that allows customers to find fintech professionals available for hire, hire them, and send them payment in the form of cryptocurrency. The customer can review a list of candidates, select one, review their hourly rate, select a quantity of time to hire them for, and hire them by submitting payment to their Ethereum account. 
  
  
## Results
---
### Application Sidebar:
![sidebar](/Images/sidebar.png)

### Sender's Account:
![sender_account](/Images/sender_account.png)

### Recipient's Account:
![recipient_account](/Images/recipient_account.png)

### Transaction Details:
![transaction_details](/Images/transaction_details.png)

---

## Technologies

The application is written in Python
The following packages are used:

Streamlit - to create the web application [Streamlit documentation](https://docs.streamlit.io/en/stable/)

os - miscellaneous operating system interfaces [os documentation](https://docs.python.org/3/library/os.html)

Requests - HTTP library for python [Pandas documentation](https://docs.python-requests.org/en/master/)

Dotenv - to read and add a key-value pair to an environment [Dotenv documentation](https://pypi.org/project/python-dotenv/)

Dataclass - provides a decorator and fucntions for automatically adding special methods to user-defined classes [Dataclass documentation](https://docs.python.org/3/library/dataclasses.html)

BIP44 - Bitcoin improvement proposals - [BIP44 documentation](https://www.cs.utexas.edu/users/moore/acl2/manuals/current/manual/index-seo.php/BITCOIN____BIP44?path=3370/27092/5157/6093/9771)

Web3 - an Ethereum Javascript API - [web3 documentation](https://web3js.readthedocs.io/en/v1.3.4/)

---

## Installation Guide

Install the Streamlit library using the following command: 'import streamlit as st'

Install the os library using the following command: 'import os'

Install the Requests library using the following command: 'import requests'

Install the dotenv library using the following command: 'from dotenv import load_dotenv'

Install the Dataclass library using the following command: 'from dataclasses import dataclass'

Install the BIP44 library using the following command: 'from bip44 import Wallet'

Install the web3 libraries using the following commands: 'from web3 import Account', 'from web3.auto.infura.kovan import w3', 'from web3 import middleware', 'from web3.gas_strategies.time_based import medium_gas_price_strategy'

--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'streamlit run fintech_finder.py' then interact with the web interface that opens.

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
