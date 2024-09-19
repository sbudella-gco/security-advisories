# security-advisories
Security advisories for issues found by Asymmetric Research. Please also see our [blog](https://www.asymmetric.re/blog).

|Title|Description|Author|
|-----|-----------|------|
| [Polygon Heimdall - Ethereum Log Confusion](./advisories/2024-02-08_polygon-heimdall_ethereum-log-confusion.md) | A log confusion vulnerability that allows Heimdall to be coerced into parsing specially crafted events as highly sensitive events, that could lead to taking over the network's consensus layer. | [Felix Wilhelm](https://x.com/_fel1x) |
| [Cosmos IBC - Reentrancy Infinite Mint](./advisories/2024-04-16_cosmos_ibc-reentrancy-infinite-mint.md) | A reentrancy vulnerability during the handling of timeout messages could have allowed an attacker to mint an infinite amount of IBC tokens on affected Cosmos chains. | [Max Dulin (Strikeout)](https://x.com/Dooflin5) |
| [Evmos - Distribution Precompile Denial of Service](./advisories/2024-06-19_evmos_distribution-precompile-denial-of-service.md) | A vulnerability in the Distribution precompile that allows allocating large chunks of memory, leading to out-of-memory exceptions. | [Jason Matthyser](https://x.com/pleasew8t) |
| [Evmos - Precompile State Commit Infinite Mint](./advisories/2024-08-01_evmos_precompile-state-commit-ininite-mint.md) | Due to incorrect state commits during precompile execution, it is possible to introduce discrepancies in the EVM state that could be abused to mint native tokens.| [Jason Matthyser](https://x.com/pleasew8t) |
| [Circle - Noble CCTP Mint Bug](./advisories/2024-08-27_circle_noble-cctp-mint-bug.md) | A vulnerability that could have been exploited by circumventing the CCTP message sender verification process to potentially mint fake USDC tokens on Noble. | [Ruslan Habalov](https://x.com/evonide) |
| [Ethereum - Ghost in the Block](./advisories/2024-09-19_ethereum-ghost-in-the-block.md) | Slight nuances in SSZ deserialization between the Prysm and Lighthouse clients could have allowed an attacker to degrade Ethereum consensus. | [Giuseppe Cocomazzi](https://www.sbudella.altervista.org) | 
