# Address Classification

In this exercise, let's expand upon the problem of node classification in our graph database, as discussed earlier. Our graph database comprises two types of data: 1. nodes representing wallet addresses, 2. directed edges between nodes representing transactions. We have structured data with numerical values only. Our goal is to spot anomalies in the transactions and identify the wallets associated with these transactions and assign a risk level to it.

Please proceed with designing and implementing a model for this purpose, and train it using the porvided data in `transactions.csv`.
For simplicity's sake, there will be no properties on the nodes, only properties on the edges.

transaction example:
```python
{
  # recipient wallet
  "to": "1Fk3kobqRuBoXrMELAL8SMTJFsCfJxvs7e",

  # transaction timestamp
  "timestamp": "1.686826847E9",

  # input value from the sender
  "input": "3597800",

  # transaction hash
  "hash": "0d4daadf6f906cca861199bc15175020efd711d5d0720472a0fc86acdf48aba6",

  # sender wallet
  "from": "bc1qx3yveuthyq0gud9nmnq5npg7qjzzg8n0e5pps5",
  
  # output value from the transaction
  "output": "3598336"
}
```

Note that this dataset is only a sample of a larger dataset, you might not be able to extract meaningful insight. Therefore the result is not very important, we are interested in your process and how you approach the problem. Please provide detailed explainations in every step of your solution.