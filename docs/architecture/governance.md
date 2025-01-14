# Governance

As a common-good project, the bridge and its components will be exclusively governed by Polkadot's governance. Specifically, the [Gov2](https://polkadot.network/blog/gov2-polkadots-next-generation-of-decentralised-governance/) governance model that is being proposed for Polkadot.

This promotes decentralisation in the following ways:

* No power is vested in centralised collectives or multisigs
* Snowfork and its employees will have no control over the bridge and its locked-up collateral
* Anyone can participate in governance, from normal users to elected members of the Polkadot fellowship

## Cross-chain Governance

Our bridge has contracts on the Ethereum, and these contracts need to be able to evolve along with the parachain side. Cross-chain governance will control both configuration and code upgrades on the Ethereum side.

As a prime example, Polkadot and BEEFY consensus algorithms will change, and so we need to make sure the Ethereum side of the bridge remains compatible. Otherwise locked up collateral will not be redeemable.

Smart contract upgrades and configuration changes will be triggered by Polkadot governance through the use of cross-chain messaging secured by the bridge itself.





