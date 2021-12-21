# Opensea-Owners-Checker
![image](https://user-images.githubusercontent.com/72508418/146925319-fa7964f0-45e3-4246-ab67-db6e15dad26c.png)

A simple Python script to **retrieve Owners/Holders of a whole NFT collection on ETH (OpenSea)**.

This can be useful for any NFT project staff to Snapshot the actual holders



# Installation

#### 1)  ```git clone https://github.com/gbe3hunna/Opensea-Owners-Checker.git```

#### 2)  ```cd Opensea-Owners-Checker && pip install -r requirements.txt```

# Other requirements

- OpenSea Collection Path/Slug 
  - `Example: https://opensea.io/collection/dos-punks` --> `dos-punks`
- Contract Address
  - `Example: https://opensea.io/collection/dos-punks` --> `0x495f947276749ce646f68ac8c248420045cb7b5e`
- Total Minted / Total Collection Tokens
  - `Example: https://opensea.io/collection/dos-punks` --> `497`
- Moralis Web3 API Key (FREE)
  - https://admin.moralis.io/web3Api


# Usage

#### Running with user input
```
python os-checker.py
```
- Fill the inputs with your data
- Filter is `OPTIONAL`


#### Running with flags
```
-s, --slug / Slug
-c, --contract / Contract Address
-m, --minted / Total Minted - Total Collection Tokens
-k, --apikey / Moralis Web3 API Key
-f, --filter (OPTIONAL) / Filter by Tokens (2 If you want to filter by holders with 2 or more tokens...)
```


