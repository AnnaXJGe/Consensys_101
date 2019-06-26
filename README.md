# Consensys_101
notes of blockchain and ethereum

## Week One Big Picture
### 1.1 overlook of the stack 
1）frount-end: React

2）API layer: WEB3----web3.py

(MORE: node.js,typescript）

3）transaction layer: golang(geth),Kotlin

4）Kaleido(private network Baas) and Infura(gateway to punlic network)

----

5）Database

6）AWS EC2/EKS

### 1.2 GraphQL
a query language for APIs and a runtime for fulfilling those queries with your existing data.

a complete and understandable description of the data in your API

complete type system

combine multy RUSTful requests into one

N+1 issue

Three layers:
1) https://graphql.org/

2) https://graphql.org/code/ 

3) Relay or appollo-client, etc.


### 1.3 Kaleido


 fully-encompassed SaaS (Software as a Service) platform 
 
 
 simplify the process of building out consortia and bootstrapping private blockchain networks
 
 
 provides a “permissioned” implementation of the Ethereum protocol
 
 member participants operate with authenticated identities backed by digital certificate chains
 
 #### Prerequisites
 
 --REST API 
 --applications and CLI
 
 #### create network
 
####  API 101

API key

export APIURL="https://console.kaleido.io/api/v1"
export APIKEY="YOUR_API_KEY"
export HDR_AUTH="Authorization: Bearer $APIKEY"
export HDR_CT="Content-Type: application/json"

JSON Sytnax

Create consortium

Create environment

Create node

https://docs.kaleido.io/developer-materials/api-101/

 
### 1.4 Infura

from truffel to Infura

HDWalletProvider object

var HDWalletProvider = require("truffle-hdwallet-provider");

var mnemonic = "orange apple banana ... ";

network---Ropsten

contract

geth attach infura









### 1.5 web3(.py)


Web3.js talks to The Ethereum Blockchain with JSON RPC, which stands for "Remote Procedure Call" protocol.


#### Web3 Technology Stack

#### web3.js

http://www.dappuniversity.com/articles/web3-js-intro


## Week Two

### 2.1 Test net
#### 2.1.1 Rinkebey

https://www.rinkeby.io/#stats

#### 2.1.2 Fancet

The ether faucet is running on the Rinkeby network.

In order to avoid spam attacks, requests are tied to twitter (or FB).

1) Make a tweet with Ethereum Address pasted into the contents.
2) Copy-paste the tweet url into Rinkeby Faucet and choose "give me Ether"

truffle---Infura---Rinkebey

#### 2.1.3 Ganache

previously testRPC

https://github.com/trufflesuite/ganache/releases

version 2

docs: https://truffleframework.org/docs/ganache/using

### 2.2 Truffle tutorial

https://www.trufflesuite.com/tutorials


### 2.3 Cryptozombie Review


A serious of coding games that help people to start learning Blockchain.

https://cryptozombies.io/

notes available:
https://github.com/loomnetwork/cryptozombie-lessons

https://github.com/loomnetwork/cryptozombie-lessons/tree/master/zh


## Week Three

### 3.1 Enterprise chain -- Hyper Ledger
https://hyperledger-fabric.readthedocs.io/en/release-1.2/tutorials.html


### 3.2 Smart contract tutorial
https://github.com/monax/legacy-docs

### 3.3 Developer Program On Demand
https://consensys.net/academy/ondemand/

## Week Four

### 4.1 Authentication vs Authorization

https://www.okta.com/identity-101/authentication-vs-authorization/

Authentication means confirming your own identity, 

while authorization means granting access to the system. 

In simple terms, authentication is the process of verifying who you are, 

while authorization is the process of verifying what you have access to.

### 4.2 Oauth2 & OIDC

Video: introduction

https://www.youtube.com/watch?v=996OiexHze0


Tutorial: Flask & OKTA

https://developer.okta.com/blog/2018/07/12/flask-tutorial-simple-user-registration-and-login


https://www.jerney.io/secure-apis-kong-keycloak-1/
