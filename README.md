# ✨ Crypto Xmas ✨


## Send Christmas Nifty tokens & Support Venezuelans

Send Christmas Nifty token, and a Ether Christmas Gift to your friends and family via a simple shareable link. Using the [Volca's "claim link" technology](https://volca.tech/), your friend only needs to click the link, and does not need to have an Ethereum wallet in advance.  

![Send](/public/cryptoxmas_repo_cover.png)

## Donations managed decentralized with Giveth

All proceeds, excluding gas cost for the Nifty token creation, is donated via the decentralized charity platform [Giveth](https://giveth.io/) to a transparent and traceable charity campaign distributing food to Venezuelans in need.  

## How it works

1) Head to cryptoxmas.xyz
2) Pick and buy a Nifty token you like
3) A fee is transferred to the Giveth Venezuela campaign
4) Share the link with the friend you want to surprise


## Not happy with your present? 

All Crypto Christmas Nifty token, with or without Ether, can be traded on [OpenSea](https://opensea.io/).

## Non-custodian escrow via eth2.io


### Sending flow

- The sender buys Christmas Nifty token by sending ETH covering the tx fee and donation fee to an escrow Smart Contract.

![Send](/public/buy_flow_server-less.png)

### Receiving flow

- The receiver claims Christmas Nifty token and optional Ether. The escrow Smart Contract transfers the Christmas Nifty token from the website's address to the receiver’s address

![Receive](/public/claim_flow_server-less.png)

### Video demo 
* [Receiving demo](https://twitter.com/dobrokhvalov/status/1071440314169208834)

## Deploy locally

To deploy web app locally clone this repo and run: 
```
npm i && npm run start
```
This will install libs and open web app at localhost:3000.  
By default web app is configured to work with our smart-contracts currently deployed on Ropsten.  
  
If you want to play with smart-contracts - [see here](https://github.com/VolcaTech/cryptoxmas.xyz/blob/master/cryptoxmas-contracts).  
If you want to configure web app to use your smart-contracts, please update `dapp-config.json` accordingly.

## Join us

Pick an issue or join us in https://t.me/CryptoXmas ✨

