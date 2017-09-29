# Predicting Ethereum Gas Prices

## Motivation 

Blockchain technology has been embraced in recent years as a common method of dealing with transactions. It has advantages that reach far beyond the tradition systems that have been used for decades. Some of the benefits include peer-to-peer networks for transactions, which eliminate the necessity of intermediates such as administrators or banks. Moreover, it is a decentralized platform which translates to faster transactions as well as reduction of the risk of fraud.  

### What is gas?

Each ethereum transaction specifies a "gas limit" and "gas price". 
- Gas limit: the total amount of gas that is alloted for a given transaction. If the limit is reached, the transaction will stop. This prevents infinite loops.
- Gas price: the price per unit gas. Miners typically approve transactions with higher gas prices. 

The outcome of a transaction depends on gas:
- A successful transaction will complete, the miner will get a reward, and the remaining gas is returned to the sender.
- A transaction runs out of gas before it completes, so it fails. The consumed gas is not refunded to the sender. 

## Summary
