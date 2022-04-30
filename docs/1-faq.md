---
sidebar_position: 1
title: FAQ
---

##  How do I get JUNOX to test the creation of a token on the testnet network?

Make a request in the #faucet channel of the Juno's discord.

##  Why doesn't my contract show up in Juno Blueprints?

Currently, Juno Blueprints is only compatible with testnet. Any contract created on the mainnet is currently not available through Juno Blueprints, once it supports the mainnet you will be able to find it.

##  How do I add a logo for my token?

The "Hello" and "Simple" tokens do not accept the addition of a logo. If you did not add a logo when you created your token, you can add one from the Asset Management page, accessible from the Assets page (then click on the Settings icon).

##  Is it possible to change the type of token once created? For example, from a Simple or Standard token to Burnable or Unlimited?

Once the token is created, it is not possible to modify its type. Only the logo can be modified.

##  Why the add token button in Keplr does not work?

You probably added the chain from a website that does not offer CW20 tokens in the Juno Network chain configuration. Delete the Juno Network chain from Keplr and add it from JunoMint and you should then be able to add the token in Keplr from JunoMint through Assets > Assets Managements > Export in Keplr.

##  How does the Juno Mint decimals system work?

If you want a supply of 100 $XTOKEN you have to put 100 and somes zero depending on the decimals point, if you have 3 decimals, you need to add 3 zeros, so 100000 for 100 $XTOKEN.
