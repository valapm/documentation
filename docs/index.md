# Vala.ai Documentation

## What is Vala?

Vala is an open-source platform for peer-to-peer prediction markets running on Bitcoin SV.

## Is Vala trustless?

The correct state of Vala including every market, trade and oracle is enforced by miners and can be deterministically generated from the current state of the blockchain.

There is trust required in the oracles. See the [Oracle FAQ](faq/oracles.md) for details.

## Is Vala censorship-resistant?

Yes, to the degree that Bitcoin itself is censorship-resistant. Nobody can prevent you from broadcasting valid transactions to trade in markets or do anything else in Vala, except a majority of Bitcoin's hashrate. While we could theoretically censor some transactions or fake information in our backend, there is nothing preventing you from broadcasting them directly or running your own backend.

## Is Vala open-source?

Yes. All scripts and logic, the frontend and code used to generate transactions as well as the wallet are open-source and available on [Github](https://github.com/valapm). At the moment, the only exception to this is our backend server whose only job is to collect and broadcast transactions and deliver the current state of Vala.
