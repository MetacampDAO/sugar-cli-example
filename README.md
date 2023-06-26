## 📗 Learn

Mint your own NFT dog collection with Sugar CLI in six steps. 

### Set up a wallet, install Sugar CLI, and mint your NFTs

1. Download and create a wallet to view your NFTs
    - For Backpack: https://www.backpack.app/downloads
    - Create username and Solana wallet

2. Download and install Sugar CLI
```sh
# For Mac / Linux / WSL
bash <(curl -sSf https://sugar.metaplex.com/install.sh) 
```

3. Create config file for uploading assets and setting up candymachine
```sh
sugar create-config
# Use your wallet public key
```

4. Airdrop 2 SOL and upload assets (it's NOT on Solana)
```sh
solana airdrop 2
sugar upload
```

5. Deploy candymachine to Solana assets
```sh
sugar deploy
```

6. Mint NFT to your wallet publickey
```sh
sugar mint --receiver YOUR_WALLET_PUBKEY
```

### Other Resources

- Metaplex Docs: https://docs.metaplex.com/programs/token-metadata/overview 
- Mint NFT: https://www.famousfoxes.com/foxymint 
- Wallet Download: 
    - Backpack: https://www.backpack.app/downloads 
    - Phantom: https://phantom.app/download 
    - Solflare: https://solflare.com/download 
- CandyMachine Docs: https://docs.metaplex.com/programs/candy-machine/overview
- Sugar CLI GitHub: https://github.com/metaplex-foundation/sugar 
- Sugar CLI Guide: https://docs.metaplex.com/developer-tools/sugar/guides/ 
- Sugar CLI Sample Collection: https://docs.metaplex.com/assets/files/assets-ff6bd873ecd07b49c86faf3c7aab82d2.zip 
- Sugar CLI Configurations: https://docs.metaplex.com/developer-tools/sugar/reference/configuration 
- Sugar CLI Commands: https://docs.metaplex.com/developer-tools/sugar/reference/commands 