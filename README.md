# Ethereum Gas Price Prediction
- by **Aryan GD Singh, Pragya Singh, Rupanshoo Saxena, Saatvik Bhatnagar, for ML course(CSE343) at IIIT Delhi**

## Motivation
- ETH is a cryptocurrency. It is digital money that is global and decentralized, secured by cryptography. Ethereum is a technology that allows the transaction of the cryptocurrency Ether for a small fee. In Ethereum,  the user should purchase a number of gases for reaching a transaction consensus. Gas Limit restricts the execution time and the memory cost of the transaction. Generally, the higher the gas price, the less time spent on reaching a consensus of the transaction. In a block, transaction gas prices vary greatly, generating a gas price that is reasonable in terms of both the price and the time spent on reaching consensus is of utmost importance. Through this project, we aim to find the lowest reasonable gas price for a block using features influencing it.

## Dataset
- The datasets used were taken from the Ethereum blockchain using GCP’s BigQuery API - Transactions and Blocks. The two main entities which affect the gas price are blocks and transactions. We used the BigQuery API to join the blocks and transactions dataset and get the relevant features.
- The data files are in the Project Drive folder linked at the bottom of this README file

## Dependencies
- python3
- sklearn
- keras
- pickle
- numpy
- pandas
- seaborn
- matplotlib
- xgboost

## Repo structure
- Data - where the dataset csv files have to be stored.
- Notebooks - contains all the notebooks used in the project
- Weights - contains the saved models
- Reports - contains the project proposal, report and presentation

## Loading the models
- Run the 02_GasPricePredictor notebook and input the model you want to load and test.

## Project folder
- Find the files related to this project [here](https://drive.google.com/drive/folders/1pwM1h0ofLfHbR5A73Y-XC_OS5N8SJLpS?usp=sharing).
- IIITD folks are automatically granted access, but others are free to request too.

## Reach out to us
- Aryan: aryan19459@iiitd.ac.in
- Pragya: pragya17305@iiitd.ac.in
- Rupanshoo: rupanshoo19096@iiitd.ac.in
- Saatvik: saatvik19097@iiitd.ac.in
