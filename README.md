# BankAccountPackage

## About The Project
This project builds a package that creates a bank database of clients and balances. It allows to add new clients and respective balances, add balance, calculate taxes and interests. Also some get some interesting data such a balances Linear Regression by age.

Built With
•	Python

## Getting Started
Package is already in Pypy so you only need to pip install it as:
```bash
pip install bank_account_pizzani
```

## Prerequisites
To build the model and preprocess the data you will need the following knowledge and having Pandas insatlled:

•	Pandas

## Installation
1.	Pip install
```bash 
pip install bank_account_pizzani
```
2.	Import the function:

```bash
from bank_account_pizzani import Exporter,Account
```
  
## Usage
Once imported you either add one single client using the fucntion .add() or load a csv of clients where the first colum is: the name, second: age, third: balance.

Then yo ucan .add_blaance() to any client_id, and set a client or account type by executing set_client_category or set_account_category.

Based on account and client category an interest or charge can be applied to the account using the methods .charge() and .interest()

Finally you can export the dataframe using the method .create_dataframe() and display a Linear Regression graph on the variable Age-Balance using the mothod .LM()

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
Your Name – bpizzani92@gmail.com
Project Link: https://github.com/bpizzani/BankAccountPackage.git
