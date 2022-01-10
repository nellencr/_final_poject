# Final project - Marketplace
Deployed version url:


How to run this project locally:

**Prerequisites**

- [ ] Node.js 
- [ ] Truffle and Ganache
- [ ] git fetch --all --tags
- [ ] git checkout tags/v1.0 -b cert

**Contracts**
- [ ] Run npm install in project root to install Truffle build and smart contract dependencies
- [ ] Run local testnet in port 8545 with an Ethereum client, e.g. Ganache
- [ ] truffle migrate 
- [ ] truffle console 
- [ ] Run tests in Truffle console: test
**Frontend**
- [ ] cd client
- [ ] npm install
- [ ] npm start
- [ ] Open http://localhost:3000
**How to populate locally deployed contract with listings**

- [ ] truffle migrate
- [ ] truffle console 
- [ ] let rr = await Rentals.deployed()
- [ ] Add two listings:
- [ ] rr.addProperty(web3.utils.toWei("0.00156"), "Hämeentie 77", "Duplex with a nice view", "https://google.com","https://www.hermannikuvia.fi/wp-content/uploads/Hameentie-77-sisapiha.jpg")
- [ ] rr.addProperty(web3.utils.toWei("0.002"), "Mannerheimintie 30 A", "Duplex with a really bad view", "https://google.com","https://www.finna.fi/Cover/Show?id=hkm.HKMS000005%3Akm002zsb&index=0&size=large&source=Solr")
- [ ] Send ETH to local wallet: web3.eth.sendTransaction({ from: "<your local address>", to: "<your local network wallet>", value: web3.utils.toWei("10") })
- [ ] cd client && npm start
- [ ] Open local ui from http://localhost:3000
- [ ] Make sure your Metamask localhost network is in port 7545.
- [ ] If you get TXRejectedError when sending a transaction, reset your Metamask account from Advanced settings.
# Screencast link
https://youtu.be/enwECpgoQUg

# Project description


.
#Simple workflow
