# Blockchain Wallets
This is the completed challenge from the 19th Module of my SMU Fintech bootcamp.

[![19-4-challenge-image.png](https://i.postimg.cc/JhjqcgMz/19-4-challenge-image.png)](https://postimg.cc/t1CW9BsK)

## Background
You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

## What You're Creating
To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.

The first file that you will use is called fintech_finder.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:

- Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

- Fetch and display the account balance associated with your Ethereum account address.

- Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

- Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

- Review the transaction hash code associated with the validated blockchain transaction.

## Streamlit

First we'll go into Git Bash and run the command streamlit run fintech_finder.py:

[![Screenshot-19.png](https://i.postimg.cc/bvS42K8w/Screenshot-19.png)](https://postimg.cc/8FDZ2Xj2)

And as you can see here it opens up and works! I was able to hire a fintech professional from the list as you can see:

[![Screenshot-18.png](https://i.postimg.cc/GpvqRrdG/Screenshot-18.png)](https://postimg.cc/hJP98kJt)

## Technologies
I completed my code using Microsoft VSC and the imported libraries of Web3 and streamlit. All the imports can be found in the py files. 

