# Kodo Exchange Token Assets

This repository contains official assets for the Kodo Exchange.

`veKDO` holders decide which liquidity **pools** receive emissions by voting on their preferred liquidity pool **gauges**. While Kodo allows permissionless **pool** creation, only *whitelisted* tokens can be included in permissionless **gauge** creation for a pool. *Whitelisting* your token on Kodo offers:

- Your token's logo in the UI for easy trading.
- Gauge creation to unlock all Kodo's features, including voting, bribing, and emissions rewards.
- Eligibility for Kodo's liquidity incentive program.

## Token Listing on Kodo

To *whitelist* a token, submit a PR with the required information to this repository. As an alternative, [open a ticket on Kodo Discord](https://discord.com/invite/p99hk4actg) to get our support!

#### Eligibility Criteria

1. The token contract must be verified.
2. The token must be paired with ETH/Stablecoins or KDO, our native token.

#### Submission Details

1. Update `tokenlist.json` with token information.
2. Add token logo to the `assets` directory (SVG or PNG, 32x32 or 128x128 preferred).
3. Description of the contract, any minting, and admin functions, including their necessity and misuse protection.
4. Description of token's current and future distribution, including community vs. team ownership, total holders, and holder distribution.
5. Incentivization plan of how to distribute tokens via voting incentives (optional).
6. Links to the project, GitHub repo or docs .
7. Telegram handle for team communication.

## Emergency Council

Requirements for *whitelisting* are critical to ensuring that our protocol cannot be exploited by actors attempting to game emissions.

To support the health of the protocol and ecosystem, the **Emergency Council** (a Curve-esque *Emergency DAO*) will have the right to disable hostile gauges.

The **Emergency Council** will initially consist of Kodo team members and members from within the Taiko community.

## Permissionless Listing Soon™

A permissionless *whitelisting* on-chain governance process will be implemented in the future, pending required on-chain governance infrastructure on Taiko.
