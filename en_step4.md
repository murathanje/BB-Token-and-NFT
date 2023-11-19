# Installation

**Before starting our project, we need to perform installations for Metamask, which we will use for blockchain interaction in our project.**

## 1- Metamask Installation
[![Metamask](https://media.giphy.com/media/doXBzUFJRxpaUbuaqz/giphy.gif)]()

Firstly, we need a [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en) wallet. ![Metamask](https://lh3.googleusercontent.com/QW0gZ3yugzXDvTANa5-cc1EpabQ2MGnl6enW11O6kIerEaBQGOhgyUOvhRedndD9io8RJMmJZfIXq1rMxUsFHS2Ttw=s20)
You can follow the detailed installation from [this link](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en).

Next, let's switch our network to the **Sepolia** network. (Sepolia is the testnet of the Ethereum network.)

Then, to use and track our BB token, let's [add our BB token](https://www.youtube.com/watch?v=2dCsY8dFak8) to our wallet.

#### Token Contract Address: `0x217151857F674683D773Ff9452BBe1C018e372c2`

## 2 - Docker Pull

Next, we have the process of pulling our project from Docker Hub. This way, we can pull our pre-built project from Docker and run it locally.

First, we pull our project:
```
docker pull kaganje/bb:latest
```
Then, we run our project pulled from Docker:
```
docker run -p 8080:8080 kaganje/bb:latest
```
**Yes!! Our project is up and running now 🥳🎉**

Now you should go to port **8080** on Cloud IT from the Bulut Bilişmciler port section.