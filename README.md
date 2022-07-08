<p align="center"><img src="width="280px""</p>

# Simplicy Vision, Mission, and Values
## **Vision:**

Transform the way peoples trades through Decentralize Smart Contract and Zero-Knoweledge technology based on open ledger, people privacy, high security and easy to use applications for average users.

## **Mission:** 
*Build to Simplify onchain payments.*

## **Values:**
- Simplify: Simplify blockchain and zero-knowledge technology to average users (ensure our products will be easy to use and understandable to users)
- User intention: Ensure our products behave as the user expects
- Trust: Build a stable platform and technology that users can trust
- Security: Build the most secure software, and minimize risk for people 
- Transparency: We allows any participant to view every transactions, because every single trades is visible to the consumer. 
- Inclusion: Build software for people across boundaries like background, ability, language, location, wealth, or computer literacy.
- Privacy: We operate according to the General Data Protection Regulation (GDPR). We'll never send the real user data to the Blockchain.
- Borderless: Bringing cost and efficiency benefits of Blockchain in cross border remittances, as removing multiple intermediary involved in traditional process.


# Products and services
- [Simplicy - zkWallet](https://github.com/zkWallet/zkWallet-docs/blob/main/README.md)
- [Simplicy - zk-ReputationService](zk-ReputationService.MD)
- [Simplicy - zk-KYC-Service](zk-KYC-Service.MD)

# Team

  
  # Simplicy - zkWallet Social Recovery
Simplicy zkWallet is a social recovery smart contract wallet using zk-SNARKS to restore a user's access to their smart contract wallet, without revealing any information of the user's and **guardians**.

## zkWallet design

- **Simplicity**: average users (non crypto users) should be able to create and use the wallet.
- **Frictionless**: most normal activities should not require much more effort than they do in regular wallet (e.g Metamask).
- **Privacy**: never send user data onchain. Must operate under the General Data Protection Regulation (GDPR).
- **Anonymous**: an account is a fresh cryptographic hash, not tied to existing systems or real-world identity. Derived paths support multiple public keys to protect privacy.

### Security

- **No single point of failure**: there is no single thing which, if stolen, can give an attacker access to user's funds, or if lost, can deny user's access to their funds.
- **Keyless**: no key's will be stored in a client web- or mobile app. 
- **Sufficient**
- **Self-Sovereign**: user's have full custody and self control of their wallet.
- **Verifieable**: trusted are only open source and hardened cryptography

### Smart contract designs

- **Open source**: community driven. Reduce the risk of vulnerabilities by using standard, tested, community-reviewed code.
- **Diamond standard upgradeable**: modular approach, simple, robust facets code.
- **Diamond storage pattern**: seperate business logics from the storage. 

## Documentation
<https://github.com/zkWallet/zkWallet-docs/blob/main/README.md>

# Sources

- [Why we need wide adoption of social recovery wallets](https://vitalik.ca/general/2021/01/11/recovery.html)
- [EIP-2535: Diamonds, Multi-Facet Proxy](https://eips.ethereum.org/EIPS/eip-2535)
- [Diamond storage pattern](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb)
