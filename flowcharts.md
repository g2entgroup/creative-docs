# Credentials, integrations, procedures and Blockchain Flowcharts

## Polygon Network (Formerly Matic)

The ARKANE API generation was successful, and we already have a key for using their services on Ethereum Staging.

For more information, we can already refer you to our documentation: [https://docs.arkane.network/](https://docs.arkane.network)

You can also check [Arketype](https://demo-staging.arkane.network), our reference implementation of the widget and check out this code on [Github](https://github.com/ArkaneNetwork/arketype) to get a head start.

The client-id is: **Creative-Platform.**

‌[**ARKANE WALLET**](https://docs.arkane.network/widget/)

For our **staging environment**, please use the following endpoints:

**Identity:** [https://login-staging.arkane.network](https://login-staging.arkane.network)

**Connect:** [https://connect-staging.arkane.network](https://connect-staging.arkane.network)

**Wallet interface:** [https://staging.arkane.network/](https://staging.arkane.network)

On Ethereum staging, we use the Rinkeby Ethereum network.

## Ethereum Staging

[**INFURA**](http://infura.io) **ID** (on Rinkeby Test network): xxxxxxxxxxxxxxxx

[**FORMATIC**](https://fortmatic.com) **API KEY:**

Testnet: pk\_test\_xxxxxxxxxxxxxxxx

Production (localhost): pk\_live\_xxxxxxxxxxxxxxxx

[**PORTIS**](https://www.portis.io) **API KEY**: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

[**ALCHEMY**](https://www.alchemyapi.io) **API KEY**: xxxxx\_xxxxxxxxxxxxxxxx

[**ETHERSCAN**](https://etherscan.io) **KEY**: xxxxxxxxxxxxxxxxxxxx

SKALE Credentials

S-Chain Name shapely-tyl

Chain ID 0x4000e5c5faac7

****

Address designed for development: PENDING.

Chakra & Next.js for UI ([discord channel](https://chakra-ui.com/discord))

Polygon (for off-chain network)

Chainlink Verification:

The Graph (api’s integrations)

Aave (lending platform)

Diamond Standard (EIP-2535): NFTs

Community.xyz (DAO)

[Superfluid](https://www.superfluid.finance) (for streaming-value)

## Procedures for MVP

Here you find the way to make your work code as is to start developing

Building the PoolTogether tripod ([Pool-Contracts](https://github.com/g2entgroup/creative-contracts)+[BuilderUI](https://github.com/g2entgroup/pooltogether-pool-builder-ui-going-to-creativeUI-)+[ReferenceUI](https://github.com/g2entgroup/pooltogether-reference-pool-ui-going-to-creativeUI-)): Please follow the **README copy.md** of every repository taking into account that depending on the environment you are trying to launch there will the conditions to be met. For that reason, there are files such as Constants.js storing credentials or hardhat.config.js/hardhat.network.js/next/config.js/etc that retrieve specific data to have a customized deployment.

## Blockchain Flowcharts

This space is used to post all the information regarding trials you can run. The trials you might need on a regular basis might be transactions mostly but most importantly the behavior of the network overall and with the changes applied through our smart contracts.

The process is the following:

1. In order to use the flowcharts you will need test ETH. Get them from the available faucets: [Rinkeby](https://faucet.rinkeby.io), [Göerli](https://goerli-faucet.slock.it), [Ropsten](https://faucet.ropsten.be), [Kovan](https://kovan.faucet.enjin.io).
2. The platform you will use to visualize such trials is [eth-build](https://eth.build). This works as a playground where you can prototype constructors, code structures you are building, etc. It is highly recommended checking the [tutorials available](https://www.youtube.com/playlist?list=PLJz1HruEnenCXH7KW7wBCEBnBLOVkiqIi) on the topic to understand how to use it:

![](.gitbook/assets/5.png)

Examples already build:

1. Transaction between Accounts on Rinkeby.
2. [NFT Unique hash creator](https://sandbox.eth.build/wofCrGxhc3Rfbm9kZV9pZMONATDEgcSDxIVsaW5rxIvEjQJFwqXEh8SJc8KYworCosSMxI4rwqR0eXBlwq1EaXNwxIJ5L1dhdGNowqNwb3PCksONAsOaxI42wqRzaXplxLwDMTzCpWbEgmdzwoDCpW9yxIlyBMKkbcSIZQDCpsSVcHV0c8KRwoTCpG5hbWXCoMSmxKjFmsKkxJTElsS9PsKlxIJiZWzCoMKnb8WfxZ7FoMWixaTFpsWoxarEqQDFssSVa3PDgMWyYcW0xbbCqnByb8SpcnRpZXPCgcKlxpN0bGXCpcSzxLVoxKHEowEsxoHEqlN0csSVZy9MZW5ndMS3xLnEu8S9w6TEjsK4xYLFhMWGw4zCjBrFi8WNxY\_FkcWTZXIFxZfFmcWbxZ3Fn8WhwoPFvsWnwqbEhMapxq\_GpceQxqjGqsWtxoXEvUDFuMW6x4vFvcWlx4\_Gm8avxrHHlG51bcW0csaExJbGh8aJxotCxo3Gj8aRxpPGlcKAxqHEjQEtxqXEq8StxK9hxLFDb2zFksS4xLrFhyDDjMK0xrnFhcKSxrwyxr9hxY7FkMWSxZQHx4fEiceJbsW7xaHFo8egxoDEp8aCx5jFrwJBx67FtcW3xbl0yJvHn8W\_xanIoMWax6vGhsaIxbPIp8exxpDHhMe0c8KCxphpxprGnMiByIPHqnZhbHVlwqY4MThhZmHHt8SOKMalwqtDcsSodG8vSMSDxrLIhsS9HMSOIsiLxYZ4HsiQyJLHgsWUA8iXxZrFnMiax57HjciewqXHinTHu8eRxqosx6bHqMeEyKJrxL1Fx5zIqsmvx45lwqRoyZvHlMm2xq\_IsXPCk8Wwx5rEvcewxo7It8aSxpTFj8mPAS7GpcKwxqfHksarU3ViypzGqsiFxrQCRGTJosKCwqEww4zCvsKhMULJpseByJTHhAbJq8iZyJvCk8mwxb\_HlcqdxqUAybzKkMq7xafCpcSEYcaSx6XHp8epy4ECQ8uDyYfHosawaMuJybpyy4xEyoDIq8uPwqbIqcW7yojHlsqKxa7GhsKRxL1ByLbHs8qVyLvLhsaSAsKmy5HGsQbKlzDGpcKsScmudC9Oy4rHhMqkxLwBNsOMxanFg8iMyq3Ij8WMyJHKs8eDcsuAxZjImMmty5rKg8iuxavLgMuiw4DLmcqCyJ7MksSpwqbJucepyovLpMqmy6fIuMqVwoPCq8e-Y2VoyILFlMKhI8i8yL7Cpsu6y5XCpcmDyYVlwqE2ypcvy7TLtsW7y7nLu3LLvcSOVDLJosiNwr7MhseAyJPMigHKt8yPzJjIrcq\_ybzMlsudzZDFp8yayYfMnceEzJ\_EvUPMosqUxpXMpcynzKnMq8eEzK3Mr8abzLHNgMy0yYTJhsKhMsqXKcalwrHGp8WSyJFlL0ZpxpsgRMeyy73DjMKWxI5KzYbDjMOCJMqyzYvFlALKt8yXxbzLm82VybTIr8q9xqrNnMSazahlwqlORlQgSU5QVVTNn8i5woHCpGbNu2XCont9yovCl86CAj7JkADEpAAAzrBAzrPEjizFm8qJZ86wQcSOLs60x7nOts6wQs66ypjPhs2dxI4vz4QuAcyczYDOsETEjjDPj8utzZpyzrBFxI4pz4QoAMKtzr7JuM2AwqZnxo91cHPCkMKmY29uzqhnwoDCp3bHhMWDz7DDiz\_DmcKZz73PvcKa)
