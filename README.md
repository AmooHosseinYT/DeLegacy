# DeLegacy
A Web3 token project inspired by cultural heritage, written in Move for the Sui blockchain.
delegacy/
│
├── README.md                 
├── Move.toml                 
├── sources/
│   └── delegacy_token.move   
├── LICENSE                   
├── assets/
│   └── logo.png              
├── docs/
│   └── tokenomics.md        
# DeLegacy Token

DeLegacy is a cultural heritage-inspired Web3 token built on the Sui blockchain using the Move language. This token represents the value of preserving legacy in decentralized systems.

## Features

- Written in Move
- Fully decentralized logic
- Tokenomics inspired by real-world legacy systems

## How to Use

Coming soon...

## License

MIT
[package]
name = "DeLegacy"
version = "0.0.1"

[addresses]
delegacy = "0xYourAddressHere"

[dependencies]
Sui = { local = "./sui-framework" }
module delegacy::token {

    use sui::coin;
    use sui::object;

    public fun create_delegacy_token(account: &signer) {
        // Create a token with fixed supply
    }

    // سایر توابع مربوط به انتقال، نگهداری و اطلاعات توکن
}
# Tokenomics

DeLegacy Token

- Total Supply: 1,000,000
- Allocation:
  - 50% Community
  - 25% Team
  - 15% Ecosystem Grants
  - 10% Reserve

Vesting Period: 2 years

Utility:
- Governance
- Legacy NFTs minting
- DAO access
![DeLegacy Logo]()


