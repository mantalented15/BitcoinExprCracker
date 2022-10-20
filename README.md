# BitcoinExprCracker

This project is the result of a personal study on the Secp256k1 algorithm. His objective is to obtain, using only the
public key values, the correct private key value.

The implemented algorithm, in a pseudorandom way, generates mathematical expressions using the values of the public key that
result in the correct value of the private key at a given position.

In the figure below an example of the algorithm showing the expressions generated for each byte in the private key:

![alt text](https://github.com/jairopaiva/BitcoinExprCracker/blob/master/Main_MostrarExprs.PNG)

Result using the values from 1 to 5 as the private key:

![alt text](https://github.com/jairopaiva/BitcoinExprCracker/blob/master/Main.PNG)
