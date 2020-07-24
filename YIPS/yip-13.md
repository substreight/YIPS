---
yip: 13
title: Remove YFI burning
status: WIP
author: Sunil Srivatsa (@alphastorm)
discussions-to: <TODO>
created: 2020-07-24
---

## Simple Summary
Remove YFI burning from the protocol.

## Abstract
All yEarn fees (currently ~$60/wk) are routed to this Vault and normalized to aDAI.

YFI represents a claim on those fees. To claim fees, YFI can either be burned or staked in the Fee Rewards pool.

This YIP is to decide whether or not to keep the burning mechanism.

## Motivation
It makes no sense to burn because the price of YFI will always be higher than the claimable fee value. This is because YFI represents current assets in the fee pool plus future expected cashflows. Staking is just obviously better.

**FOR**: Remove YFI burning from the protocol.

**AGAINST**: No change.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
