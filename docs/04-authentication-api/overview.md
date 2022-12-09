---
title: "Overview"
slug: "/authentication-api"
sidebar_position: 1
--- 

![](https://files.readme.io/594b455-image.png)

## What is the Auth API?

Auth API allows your user to authenticate and verify signed messages with their web3 wallets when using your dapp. Built accordingly to the [EIP-4361](https://eips.ethereum.org/EIPS/eip-4361) standard, enables your user to do off-chain authentication with their EVM or Solana-compatible wallets to establish user sessions with your dapp.

## Auth API Features

The Auth API provides out-of-the-box all the necessary APIs you need to authenticate your user wallet to your dapp, which includes:

- Requesting challenge message for wallet signature on both [EVM](https://docs.moralis.io/reference/requestchallengeevm) and [Solana](https://docs.moralis.io/reference/requestchallengesolana)
- Verifying signed challenge message signature on both [EVM](https://swagger.moralis.io/auth/#/Challenge/verifyChallengeEvm) and [Solana](https://swagger.moralis.io/auth/#/Challenge/verifyChallengeSolana)

> 📘 The Auth API currently does not support [EIP-1271](https://eips.ethereum.org/EIPS/eip-1271) signature. Therefore, authentication using the Auth API with smart contract wallet is impossible.

## Popular use cases

The use cases for our Auth API are truly endless! Some popular use cases include:

- [Sign in with Metamask](https://docs.moralis.io/docs/sign-in-with-metamask)
- [Sign in with WalletConnect](https://docs.moralis.io/docs/sign-in-with-walletconnect)
- [Sign in with RainbowKit](https://docs.moralis.io/docs/sign-in-with-rainbowkit)
- [Sign in with Coinbase Wallet](https://docs.moralis.io/docs/sign-in-with-coinbase-wallet)
- [Sign in with Web3Auth](https://docs.moralis.io/docs/sign-in-with-web3authio)
- [Sign in with Magic.link](https://docs.moralis.io/docs/sign-in-with-magiclink)