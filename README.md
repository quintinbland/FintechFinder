# FintechFinder
An application that allows users to find a fintech professional, hire and pay them. 

---
## Installation

* [ganache](https://trufflesuite.com/docs/ganache/)

* [streamlit](https://docs.streamlit.io/library/get-started)
```
!pip install streamlit
```

## Usage

1. Navigate to the project folder that contains 
your `.env` file and the `fintech_finder.py` and `crypto_wallet.py` files.
Be sure to activate your Conda `dev` environment if it is not already active.

2. To launch the Streamlit application,
type ```streamlit run fintech_finder.py```

3. On the resulting webpage, select a candidate that you would like to hire
 from the appropriate drop-down menu. Then, enter the number of hours that you
 would like to hire them for.

4. Click the Send Transaction button to sign and send the transaction with
 your Ethereum account information. If the transaction is successfully
 communicated to Ganache, validated, and added to a block,
 a resulting transaction hash code will be written to the Streamlit
 application sidebar.

5. Navigate to the Ganache accounts tab and locate your account (index 0).

6. Navigate to the Ganache transactions tab and locate the transaction.


- My Address Balance
![ganache_address_balance_tx](https://user-images.githubusercontent.com/97932685/181120638-54149610-d849-46c0-8e62-2ae668cdf2e3.png)

- Transaction Details
![ganache_transaction_history](https://user-images.githubusercontent.com/97932685/181120742-eaa9b862-7316-44dd-b336-d5fd74a94cde.png)

- Recipient's Address Balance
![ganache_to_address](https://user-images.githubusercontent.com/97932685/181120777-be97a7e1-6b64-44c7-afce-f7fc8f0dad3d.png)

insert image here
insert image here
---



## Contributors


*  **Quintin Bland** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* quintinbland2@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> <a href="https://www.linkedin.com/in/quintin-bland-a2b94310b/"><img src="https://img.shields.io/badge/-Quintin_Bland-0077B5?style=flat-square&logo=Linkedin&logoColor=white"/></a> 

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
