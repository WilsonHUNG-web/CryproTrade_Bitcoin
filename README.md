# CryproTrade_Bitcoin

--How to run

This is a simple code which can generate a block hash with provided block height and nonce to verify the correctness of the nonce.
And the second part also provide a virtual mining method to mine BTC according to the lastest block info online.

1.	Firstly install the blockcypher package by the command:
```
$ pip3 install blockcypher
```
2.	To verify the nonce, run 109065527_MidTerm_Project_Nonce_verifier.py by the command:
```
$ python 109065527_MidTerm_Project_Nonce_verifier.py
```
Ps.
If you want to specify the Height and Nonce, go to the bottom line in this *.py file and edit the function input of cal_block_hash(Height, Nonce) as shown below.

3.	To start mining, run the 109065527_MidTerm_Project_Mining.py by the command:
```
$ python 109065527_MidTerm_Project_Mining.py
```
