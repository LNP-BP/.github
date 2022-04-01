# LNP/BP Standards Association 

We are Swiss non-profit **supervising layer 2 & 3 protocols on Bitcoin & Lightning Network** 
(LNP/BP stands for "Bitcoin Protocol / Lightning Network Protocol").

We manage set of standards (LNPBP standards) and do reference implementations.

The Association is founded and managed by @dr-orlovsky and @giacomozucco since 2019.

## LNPBP Standards

The current list of standard can be found [here](https://github.com/LNP-BP/LNPBPs). You can:
- [submit](https://github.com/LNP-BP/LNPBPs/discussions/categories/standard-proposals) a new standard proposal
- [discuss](https://github.com/LNP-BP/LNPBPs/discussions/categories/ideas) preliminary ideas about new standards
- [follow announcements](https://github.com/LNP-BP/LNPBPs/discussions/categories/releases) about standard releases
- [write](https://github.com/LNP-BP/LNPBPs/discussions/categories/implementations) about your implementation of one of the standards
- [ask questions](https://github.com/LNP-BP/LNPBPs/discussions/categories/q-a)
- [peer review & audit](https://github.com/LNP-BP/LNPBPs/discussions/categories/peer-review) existing standards

## Working groups

The reference implementations are split across multiple GitHub organizations,
maintained by a working groups inside the Association.
- @RGB-WG: scalable & confidential smart contracts for Bitcoin & LN with client-side-validation
- @LNP-WG: lightning network protocol evolution
- @Storm-WG: protocol for trustless decentralized & incentivized data storage network on top of Lightning network with bitcoin native payments
- @Prometheus-WG: protocol for trustless decentralized & incentivized computing network on top of Lightning network with bitcoin native payments
- @Internet2-WG: AluVM virtual machine and network protocol implementations

## Libraries and products

LNP/BP Association is major contributor into @rust-bitcoin projects; @dr-orlovsky 
(founder and lead engineer of the Association) is one of maintainers of 
[rust bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) implementation. 

Other reference implementations & products maintained by the Association include:
- [Client-side-validation library](https://github.com/LNP-BP/client_side_validation/);
- [Descriptor wallet](https://github.com/LNP-BP/descriptor-wallet/): bitcoin wallet library & cli supporting taproot, multisigs, miniscript, client-side-validation;
- [BP Core Library](https://github.com/LNP-BP/bp-core/): implementation of deterministic bitcoin commitments and single-use-seals
- [BP Node](https://github.com/LNP-BP/bp-node/): indexing node for bitcoin network (replacement for Electrum server)
- [LNP Core Library](https://github.com/LNP-WG/lnp-core/): pure rust implementation of lightning network and bifrost protocol
- [LNP Node](https://github.com/LNP-WG/lnp-core/): rust lightning node supporting bifrost protocol & RGB
- [RGB Core Library](https://github.com/RGB-WG/rgb-core/): implementation of RGB protocol
- [RGB Node](https://github.com/RGB-WG/rgb-node/): node for running RGB smart contracts
- [AluVM](https://github.com/Internet2-WG/rust-aluvm/): virtual machine used in RGB smart contracts and lightning
