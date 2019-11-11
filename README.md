# Stellarport BinanceX Proposal
BinanceX BNB &lt;-> XLM bridge proposal

## Current State
Stellarport currently operates a stablecoin service on the Stellar network. The stablecoin service can tokenize an arbitrary asset on the Stellar network. It does this by operating a central a3s hub that communicates with a set of asset specific relay servers. 

- [architecture docs](https://github.com/stellarport/binancex-proposal/blob/master/A3S_Relay_Infrastructure_Overview.pdf)
- [API docs](a3s.stellarport.io)
- [relay server skeleton](https://github.com/stellarport/relay-server-skeleton)
- [open source sdk](https://github.com/stellarport/a3s)

## Proposal
Our proposal is to enable the transfer of BNB into and out of the Stellar DEX as well as the transfer of XLM into and out of the Binance DEX. This will be accomplished in two stages:

## Stage 1 (ETA 2 months)
We will enable BNB deposits into and out of the Stellar DEX. BNB will be able to be transferred into and out of the Stellar DEX using the open source sdk. This will entail running reliable Binance Chain infrastructure to enable reliable deposits and withdrawals as well as adding a BNB relay server and adding BNB to our open source SDK and API docs.

## Stage 2 (ETA 6 months)
We will enable XLM deposits into and out of the Binance DEX. XLM will be able to be transferred into and out of the Binance DEX using the open source sdk. This will entail expanding our A3S hub to operate on multiple networks and adding Binance DEX as a valid network for the A3S hub. Then, XLM will be added as an asset relay server for the Binance DEX as well as to our open source SDK and API docs.
