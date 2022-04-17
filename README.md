# CCNSwap Assets Info

## Overview

CCNSwap token repository is a comprehensive, up-to-date collection of information about several thousands (!) of crypto tokens.

[CCNSwap](https://ccnswap.org) uses token logos from this source, alongside a number of other projects.

The repository contains token info from several blockchains, info on dApps, staking validators, etc.
For every token a logo and optional additional information is available (such data is not available on-chain).

Such a large collection can be maintained only through a community effort, so _feel free to add your token_.

## How to add token

 - Fork assets repositories
 - Add token info
 - Submit new pull requests

## Token Specification

Before submitting an asset to this repository, we recommend you have the following information handy:
 - Asset details
 -  Token Name
  
  <br/>&ensp;Symbol
  <br/>&ensp;Contract Address
  <br/>&ensp;Decimals
 - Logo
  <br/>&ensp;File Extension: png (Uppercase PNG is considered invalid)
  <br/>&ensp;File Name: logo.png
  <br/>&ensp;Size: 256px by 256px
  <br/>&ensp;Background: Preferably transparent
 - Token information file
  <br/>&ensp;File Extension: json (Uppercase JSON is considered invalid)
  <br/>&ensp;File Name: info.json
  <br/>&ensp;Required fields:
  <br/>&ensp;&ensp;name: name of the token
  <br/>&ensp;&ensp;type: such as ERC20, BEP2, BEP20, TRC20, TRC10, ...
  <br/>&ensp;&ensp;symbol: the token symbol
  <br/>&ensp;&ensp;decimals: number of decimal digits used in the amounts (e.g. 18 for ETH)
  <br/>&ensp;&ensp;description: a few sentence summary of the token/project
  <br/>&ensp;&ensp;website: project web site
  <br/>&ensp;&ensp;explorer: URL of the token explorer page
  <br/>&ensp;&ensp;id: the id/contract/address of the token, same as the subfolder name
  <br/>&ensp;&ensp;links: array with name/url pairs, for social media links, documentation, etc.
  <br/>&ensp;&ensp;tags: Assigning these tags to tokens helps place them on appropriate token menus and ensures your token is evaluated correctly in conditions.
 - Checksum address (for CRC20 tokens)
  <br/>&ensp;Checksum addresses can be found on ComputcoinScan or by using this tool

## Disclaimer

CCNSwap team allows anyone to submit new assets to this repository. However, this does not mean that we are in direct partnership with all of the projects.

CCNSwap team will reject projects that are deemed as scam or fraudulent after careful review.
CCNSwap team reserves the right to change the terms of asset submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.

Additionally, spam-like behavior, including but not limited to mass distribution of tokens to random addresses will result in the asset being flagged as spam and possible removal from the repository.
