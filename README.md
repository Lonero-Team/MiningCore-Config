# MiningCore-Config
### Blocklink/blockchain explorer API under construction
### Add Lonero to Miningcore, under coins.json file
### Integrates same hashing as Monero, because both utilize the cryptonight hash
  ```
  "lonero": {
    "name": "Lonero",
    "symbol": "LNR",
    "family": "cryptonote",
    "hash": "cryptonight",
    "hashVariant": 0,
    "smallestUnit": 1000000000000,
    "addressPrefix": 18,
    "addressPrefixTestnet": 53,
    "addressPrefixIntegrated": 19,
    "addressPrefixIntegratedTestnet": 54,
    "explorerBlockLink": "https://chainradar.com/lnr/block/$height$",
    "explorerTxLink": "https://chainradar.com/lnr/transaction/{0}"
  },
```
