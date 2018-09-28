# CryptoExchanges

The file `exchanges.py` contains a python (keys,values) dictionary listing ('Exchange Name', \['address'\]). 
The information was collected from EtherScan's labels **[Exchange](https://etherscan.io/accounts?l=Exchange)**
and **[Dex](https://etherscan.io/accounts?l=Dex)**.

### Flattening the List
To return all exchange names: `[item for sublist in DEX.keys() for item in sublist]`  <br>
To return all exchange addys: `[item for sublist in DEX.values() for item in sublist]`
