# Address Classification

In this exercise, let's delve depper into the problem of node classification in our graph database, as discussed earlier. Our graph database comprises two types of data: 1. nodes that represent wallet addresses and 2. directed edges that together represent transactions. For simplicity, we collected and prepared the dataset `transactions.csv`. Your goal is to spot anomalies in the transactions and identify the wallets associated with these transactions and assign a risk level to it.

transaction example:
```python
{
  # transaction fee
  "fee": "50400",

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

Note that this dataset is a random sample of a larger dataset, you might not be able to extract meaningful insight. Therefore the result is not very important and any level of completness is acceptable, we are interested in your process and how you approach the problem. This is an OPEN question, there are no wrong answers, just remember to provide detailed explanations.