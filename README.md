# Awesome-CrossChain

[![Awesome](https://awesome.re/badge.svg)](https://github.com/AxonDAO/awesome-crosschain)

> Curated list of awesome crosschain protocol resources and links.

## Contents
<details><summary>Click to expand</summary>
- [Awesome-CrossChain](#awesome-crosschain)
  - [Contents](#contents)
  - [Basic Introduction](#basic-introduction)
  - [Projects](#projects)
  - [Information Resources](#information-resources)
  - [Tools & Libraries](#tools--libraries)
  - [Papers](#papers)
  - [Related Resources](#related-resources)
</details>

## Basic Introduction

- [Chain Interoperability](https://allquantor.at/blockchainbib/pdf/vitalik2016chain.pdf) by Vitalik Buterin
- Atomic Swaps
    - [Bitcoin Wiki - Atomic Cross-Chain Trading](https://en.bitcoin.it/wiki/Atomic_swap)
    - [Atomic Cross-Chain Swaps](https://arxiv.org/abs/1801.09515), Maurice Herlihy, arxiv 2018.

## Projects

- [tBTC](https://tbtc.network/), a fully Bitcoin-backed ERC-20 token pegged to the price of Bitcoin.
- [Waterloo](https://blog.kyber.network/waterloo-a-decentralized-practical-bridge-between-eos-and-ethereum-c25b1698f010) — a Decentralized Practical Bridge between EOS and Ethereum.
- [polkadot](https://polkadot.network), a next-generation blockchain protocol that unites an entire network of purpose-built blockchains, allowing them to operate seamlessly together at scale.
- [cosmos](https://cosmos.network), a decentralized network of independent parallel blockchains. The connection between blockchains is achieved through a protocol called [Inter-Blockchain Communication protocol (IBC)](https://blog.cosmos.network/developer-deep-dive-cosmos-ibc-5855aaf183fe).
- [elements](https://elementsproject.org/), An open source, sidechain-capable blockchain platform develeoped by Blockstream. An example of an Elements based sidechain in production use is Blockstream’s [Liquid](https://blockstream.com/liquid/).
- arbitrum, a Layer 2 cryptocurrency platform that makes smart contracts scalable, fast, and private. [github](https://github.com/OffchainLabs/arbitrum), [docs](https://developer.offchainlabs.com/docs/Developer_Quickstart/), [ethresear.sh](https://ethresear.ch/t/introducing-arbitrum-a-new-layer-2-solution/3825/13)
- bitxhub, [website](https://www.hyperchain.cn/products/interchain)
- [bystack](https://www.bystack.com/), [vapor](https://github.com/Bytom/vapor)
- [CKB Sidechain Framework](https://talk.nervos.org/t/ckb-sidechain-framework/4722)
- [matic](https://matic.network/), brings massive scale to Ethereum using an adapted version of Plasma with PoS based side chains.

## Information Resources

- twitter
    - [Cross-Chain Group](https://twitter.com/crosschaingroup)
    - [Keep #tBTC](https://twitter.com/keep_project)
- Medium
    - [summa](https://medium.com/summa-technology), Interoperability as a Service
- Community
    - [Cross-Chain Group](https://crosschain.group/)

## Tools & Libraries

- [bitcoin-spv](https://github.com/summa-tx/bitcoin-spv)

## Papers

- SoK
    - Buterin, V. Chain Interoperability. Available: https://allquantor.at/blockchainbib/pdf/vitalik2016chain.pdf.
    - Singh, A. et al. Sidechain technologies in blockchain networks: An examination and state-of-the-art review. Journal of Network and Computer Applications 149, 102471 (2020).
    - Gudgeon, L., Moreno-Sanchez, P., Roos, S., McCorry, P. & Gervais, A. SoK: Layer-Two Blockchain Protocols. http://eprint.iacr.org/2019/360 (2019).
- chain interoperability
    - Dilley, J. et al. Strong Federations: An Interoperable Blockchain Solution to Centralized Third-Party Risks. arXiv:1612.05491 (2017).
    - Abebe, E. et al. Enabling Enterprise Blockchain Interoperability with Trusted Data Transfer (industry track). arXiv:1911.01064 (2019).
- sidechains
    - Kiayias, A. & Zindros, D. Proof-of-Stake Sidechains. http://eprint.iacr.org/2018/1239 (2018).
    - Hwang, G.-H. et al. InfiniteChain: A Multi-chain Architecture with Distributed Auditing of Sidechains for Public Blockchains. in Blockchain – ICBC 2018 (eds. Chen, S., Wang, H. & Zhang, L.-J.) 47–60 (Springer International Publishing, 2018). doi:10.1007/978-3-319-94478-4_4.
    - Gai, F., Grajales, C., Niu, J., Jalalzai, M. M. & Feng, C. A Secure Consensus Protocol for Sidechains. arXiv:1906.06490  (2019).
    - Kiayias, A. & Zindros, D. Proof-of-Work Sidechains. in Financial Cryptography and Data Security (eds. Bracciali, A., Clark, J., Pintore, F., Rønne, P. B. & Sala, M.) 21–34 (Springer International Publishing, 2020). doi:10.1007/978-3-030-43725-1_3.
    - Back, A. et al. Enabling Blockchain Innovations with Pegged Sidechains. 25.
    - Johnson, S., Robinson, P. & Brainard, J. Sidechains and interoperability. arXiv:1903.04077  (2019).
- commit-chains
    - Pass, R. & Shi, E. Thunderella: Blockchains with Optimistic Instant Confirmation. http://eprint.iacr.org/2017/913 (2017).
    - Khalil, R., Zamyatin, A., Felley, G., Moreno-Sanchez, P. & Gervais, A. Commit-Chains: Secure, Scalable Off-Chain Payments. http://eprint.iacr.org/2018/642 (2018).
- related work
    - Kiayias, A., Miller, A. & Zindros, D. Non-Interactive Proofs of Proof-of-Work. http://eprint.iacr.org/2017/963 (2017).
    - Kalodner, H., Goldfeder, S., Chen, X., Weinberg, S. M. & Felten, E. W. Arbitrum: Scalable, private smart contracts. 19.
    - Al-Bassam, M., Sonnino, A. & Buterin, V. Fraud and Data Availability Proofs: Maximising Light Client Security and Scaling Blockchains with Dishonest Majorities. arXiv:1809.09044  (2019).
    - Teutsch, J. & Reitwießner, C. A scalable veriﬁcation solution for blockchains. 50.
    - Canetti, R., Riva, B. & Rothblum, G. N. Practical delegation of computation using multiple servers. in Proceedings of the 18th ACM conference on Computer and communications security 445–454 (Association for Computing Machinery, 2011). doi:10.1145/2046707.2046759.
    - Ouroboros
        - Kiayias, A., Russell, A., David, B. & Oliynykov, R. Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol. http://eprint.iacr.org/2016/889 (2016).
        - Badertscher, C. & Kiayias, A. Tutorial: The Ouroboros Protocol Family. 214.

## Related Resources

- https://github.com/yjjnls/awesome-blockchain
- https://github.com/chaozh/awesome-blockchain-cn
- https://github.com/RobinHung/awesome-cross-blockchain
- https://github.com/Awesome-Layer-2/awesome-layer-2