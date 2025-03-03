# 🚀Solana Token 2022🚀

The Solana Program Library (SPL) includes the Token-2022 program, an extension of the original SPL Token program, offering enhanced functionality for token management on the Solana blockchain. The Token-2022 program introduces new features such as confidential transfers, transfer fees, interest-bearing tokens, and more, allowing developers to create customized token behaviors


## 📞 **Stay Connected**

Gmail: tom.kinddev@gmail.com

Telegram: [@erikerik116](https://t.me/erikerik116)

Discord: [@erikerik116](https://discord.com/channels/@me/304228787250528256)

Twitter: @erikerikerik116




# To Get Started

### Usage

1. `npm install` or yarn
2. Write code in `index.js`
3. `npm run start`

### Helpers

1. initializeKeypair:
   1. takes a connection obj
   1. takes optional filePath, if you provide the keypair file path like
      `~/.config/solana/id.json` which is the default keypair for Solana CLI it
      will take the keypair from there and consider them as payer
   1. if not it will generate a new keypair and store them in the .env to use
      them in the future with any other transaction
   1. it will airdrop SOL for the payer account if need
1. uploadOffChainMetadata:
   1. take metadata inputs like name, symbol, description, and image
   1. uploads them to an off-chain storage provide
   1. return a URI that points to that metadata JSON
