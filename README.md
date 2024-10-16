# Comprehensive Lightning Network Node Operator Resources

A curated collection of essential tools, guides, and communities for Bitcoin Lightning Network node operators.

## Introduction

This guide provides a comprehensive list of resources for Lightning Network node operators, including installation guides, management tools, security best practices, and community resources. Whether you're a beginner or an experienced operator, you'll find valuable information to help you run and optimize your Lightning Network node.

## Table of Contents

1. [Essential Reading](#essential-reading)
2. [Node Installation](#node-installation)
3. [Backups and Recovery](#backups-and-recovery)
4. [Self-Hosting Solutions](#self-hosting-solutions)
5. [Managed Cloud Hosting](#managed-cloud-hosting)
6. [Lightning Network Implementations](#lightning-network-implementations)
7. [Node Management Web Interfaces](#node-management-web-interfaces)
8. [Security Tools](#security-tools)
9. [Node Management Tools](#node-management-tools)
10. [Node Services](#node-services)
11. [Channel Management](#channel-management)
12. [Tutorials and Guides](#tutorials-and-guides)
13. [Liquidity Management](#liquidity-management)
14. [Network Explorers](#network-explorers)
15. [Communities](#communities)
16. [Watchtowers](#watchtowers)
17. [Mempool Resources](#mempool-resources)
18. [Educational Resources](#educational-resources)
19. [Network Statistics](#network-statistics)
20. [Further Reading](#further-reading)

## Essential Reading

- [Understanding Lightning Network: Comprehensive Guide by Diamond Hands](https://docsend.com/view/x2yscafayexddzps)
- [Jameson Lopp's Lightning Network Liquidity Management Guide](https://blog.lopp.net/lightning-network-liquidity-management-guide/)
- [Alex Bosworth's In-Depth Liquidity Management Strategies](https://github.com/alexbosworth/run-lnd/blob/master/LIQUIDITY.md)
- [Lightning Network Node Profitability: PLEBNET Insights](https://www.youtube.com/watch?v=LRZy-VtCPe4)
- [Running a Lightning Network Node: A Beginner's Journey](https://medium.com/coinmonks/adventures-in-running-a-bitcoin-lightning-node-part-1-the-awakening-61345585acc3)
- [Mastering Inbound Liquidity: Step-by-Step Guide](https://www.youtube.com/watch?v=WWs1D9LLcpc)

## Node Installation

### LND (Lightning Network Daemon)

- [Alex Bosworth's Comprehensive LND Installation Guide](https://github.com/alexbosworth/run-lnd)
- [Official LND Installation Documentation](https://github.com/lightningnetwork/lnd/blob/master/docs/INSTALL.md)
- [Bitcoin Kit Makefile: Streamlined Installation](https://github.com/Perlover/bitcoin-kit-makefile)
- [LND with PostgreSQL Integration](https://github.com/blckbx/lnd_postgres)
- [Secure LND Setup via VPN](https://github.com/Wired4ncer/lnd_via_vpn)
- [The Road to Node: Detailed LND Setup Guide](https://docs.theroadtonode.com/)

### CLN (Core Lightning)

- [Video Tutorial: Step-by-Step CLN Installation](https://www.youtube.com/watch?v=_Hrnls92TxQ)
- [Rootzoll's Comprehensive CLN Guide](https://github.com/rootzoll/raspiblitz/blob/dev/FAQ.cl.md)
- [RaspiBolt CLN Installation and Configuration](https://raspibolt.org/guide/bonus/lightning/cln.html)
- [Core Lightning Plugins Repository](https://github.com/lightningd/plugins)

## Backups and Recovery

- [LND Backup and Recovery Strategies](https://github.com/lightningnetwork/lnd/blob/master/docs/recovery.md)
- [Core Lightning Backup Best Practices](https://lightning.readthedocs.io/BACKUP.html)

## Self-Hosting Solutions

- [RaspiBlitz: DIY Bitcoin & Lightning Node](https://github.com/rootzoll/raspiblitz)
- [Umbrel: User-Friendly Bitcoin Node](https://getumbrel.com/)
- [MyNode: Full Bitcoin Node & Lightning Network Box](https://mynodebtc.com/)
- [NixBitcoin: Nix-based Bitcoin Node](https://nixbitcoin.org/)
- [Blockstream's Guide: Building a High-Quality Lightning Network Node](https://medium.com/blockstream/build-a-pretty-good-lightning-network-node-468778a078b7)

## Managed Cloud Hosting

- [Nodl: Professional Bitcoin & Lightning Node Solutions](https://www.nodl.eu/)
- [Voltage: Cloud-Native Bitcoin Infrastructure](https://voltage.cloud/)
- [Tidebinder: Managed Lightning Network Node Hosting](https://www.tidebinder.com)

## Lightning Network Implementations

- [LND (Lightning Network Daemon)](https://github.com/lightningnetwork/lnd)
- [Core Lightning (formerly c-lightning)](https://github.com/ElementsProject/lightning)
- [Eclair: Scala-based Lightning Implementation](https://github.com/ACINQ/eclair)
- [LDK-node](https://github.com/lightningdevkit/ldk-node)

## Node Management Web Interfaces

- [Ride The Lightning (RTL): Feature-Rich Web Interface](https://github.com/Ride-The-Lightning/RTL)
- [Thunderhub: Powerful Lightning Node Management Dashboard](https://github.com/apotdevin/thunderhub)
- [LNCLi Web: User-Friendly LND Web Client](https://github.com/mably/lncli-web)
- [Lightning Terminal: All-in-One Node Management Tool](https://github.com/lightninglabs/lightning-terminal)
- [LNDG: LND Dashboard and Graph](https://github.com/cryptosharks131/lndg)
- [Torq: Advanced Lightning Network Management Platform](https://github.com/lncapital/torq)

## Security Tools

- [Validated Lightning Signer: Enhanced Security for Lightning Nodes](https://vls.tech/)
- [Sphinx Key: Hardware Security Module for Lightning](https://github.com/stakwork/sphinx-key)
- [Lightning Vault: Secure Key Management Solution](https://github.com/bolt-observer/lightning-vault/)

## Node Management Tools

- [LN-Charts: Visualization Tool for Lightning Network Data](https://github.com/cold-sats/ln-charts)

### CLN Tools 
- [CLN Cheatsheet: Quick Reference for Core Lightning Commands](https://github.com/grubles/cln-cheatsheet)
* [lnurl-commando][lnurl-commando] - An lnurl/lnaddress server that fetches invoices over commando
- [CLBOSS: Automated Core Lightning Node Manager](https://github.com/ZmnSCPxj/clboss)
* [Rune Workshop](https://jb55.com/runes) - A web UI for constructing commando auth runes
* [c-lightning-REST](https://github.com/Ride-The-Lightning/c-lightning-REST) - REST APIs for c-lightning written with node.js

### LND Tools
- [Balance of Satoshis: Advanced Node Management Toolkit](https://github.com/alexbosworth/balanceofsatoshis)
- [BOS Commands Document: Comprehensive Guide to Balance of Satoshis](https://github.com/niteshbalusu11/BOS-Commands-Document)
- [Charge-LND: Automated Fee Management for LND](https://github.com/accumulator/charge-lnd)
- [Rebalance-LND: Channel Rebalancing Tool](https://github.com/C-Otto/rebalance-lnd)
- [CircuitBreaker: Automated Channel Management](https://github.com/lightningequipment/circuitbreaker)
- [LNDPyTools: Python-based LND Management Utilities](https://github.com/Gridflare/lndpytools)
- [Lightning Jet: Advanced Node Optimization Tool](https://github.com/itsneski/lightning-jet)
- [LNDManage: Python-based LND Management Suite](https://github.com/bitromortac/lndmanage)
- [LNTop: Top-like Monitoring Tool for LND](https://github.com/edouardparis/lntop)
- [Suez: Channel Rebalancing Script](https://github.com/prusnak/suez)
- [LND-ManageJ: Java-based LND Management Tool](https://github.com/C-Otto/lnd-manageJ)


## Node Services

- [LNRouter: Comprehensive Lightning Network Analysis](https://lnrouter.app/)
- [LN Node Insight: Advanced Node Metrics and Analysis](https://lnnodeinsight.com/)
- [Lightning Watch: Real-Time Lightning Network Monitoring](https://lightning.watch/)

## Channel Management

### Channel Opening Suggestions

- [Gridflare: AI-Powered Channel Recommendations](https://gridflare.xyz/explore/search)
- [Moneni NodeMatch: Optimal Node Pairing](https://www.moneni.com/nodematch)
- [Lightning Terminal: Channel Management Platform](https://terminal.lightning.engineering/#/)
- [Lightning Network Autopilot: Automated Channel Management](https://github.com/renepickhardt/lightning-network-autopilot)

## Tutorials and Guides

- [Lightning Node Management by Openoms: Comprehensive Guide](https://github.com/openoms/lightning-node-management)
- [Bitcoin Tutorials by Openoms: In-Depth Learning Resources](https://github.com/openoms/bitcoin-tutorials)
- [Node Liquidity Guide by Darthcoin: Mastering Liquidity Management](https://darthcoin.substack.com/p/node-liquidity-guide)
- [Lightning Cleaning Machine by Darthcoin: Optimizing Node Performance](https://darthcoin.substack.com/p/lightning-cleaning-machine)
- [Recovering Funds from Stuck Closing Transactions: Troubleshooting Guide](https://community.umbrel.com/t/the-guide-where-your-lightning-close-transaction-cant-get-the-channel-closed/15096)

## Liquidity Management

### Inbound Liquidity

- [Comprehensive Inbound Liquidity Guide](https://github.com/openoms/lightning-node-management/blob/en/createinboundliquidity.md)

### Swaps and Exchanges

- [Coinos: Instant Bitcoin-to-Lightning Swaps](https://coinos.io/login)
- [FixedFloat: Cryptocurrency Exchange with Lightning Support](https://fixedfloat.com/)
- [SideShift: Automated Crypto Trading Platform](https://sideshift.ai/btc/ln)
- [Deezy: Lightning Network Liquidity Provider](https://deezy.io/)
- [Boltz Exchange: Non-Custodial Bitcoin Exchange](https://boltz.exchange/)
- [Lightning Loop: Submarine Swaps for Liquidity Management](https://github.com/lightninglabs/loop)
- [ZigZag: Fast Crypto Exchange with Lightning Support](https://zigzag.io/)

### Liquidity Marketplaces

- [Lightning Pool: Marketplace for Lightning Liquidity](https://lightning.engineering/pool/)
- [Voltage Flow: Liquidity Management Platform](https://voltage.cloud/flow)
- [Amboss Magma: Advanced Liquidity Marketplace](https://amboss.space/magma)

### Channel Leasing and LSPs

- [LNBIG: Large-Scale Lightning Network Service Provider](https://lnbig.com/)
- [Lightning Conductor: Inbound Liquidity Service](https://mainnet.lightningconductor.net/)
- [Lightning Network Plus (LN+): Collaborative Channel Opening](https://lightningnetwork.plus/)
- [Lightning Conductor Channels: Custom Channel Creation](https://lightningconductor.net/channels)
- [LightningTo.Me: Free Inbound Liquidity Service](https://lightningto.me/)
- [Bitrefill Thor Channels: On-Demand Lightning Channels](https://www.bitrefill.com/buy/lightning-channel/)
- [Voltage Flow: Automated Liquidity Management](https://voltage.cloud/flow/)
- [Blocktank: Professional Lightning Service Provider](https://blocktank.to/)

## Network Explorers

- [1ML: Comprehensive Lightning Network Explorer](https://1ml.com/)
- [Amboss Space: Advanced Lightning Network Analytics](https://amboss.space/)
- [ACINQ Lightning Explorer: Real-Time Network Insights](https://explorer.acinq.co/)
- [LN Lighthouse: Visual Lightning Network Explorer](https://lnlighthouse.online/)
- [Bolt Observer Explorer: Detailed Network Analysis](https://bolt.observer/explorer)
- [Mempool Lightning Explorer: Bitcoin and Lightning Integration](https://mempool.space/lightning)

## Communities

- [Lightning Liquidity & Pool Telegram Group](https://t.me/LNBalancedChannels)
- [Plebnet Telegram Community](https://t.me/plebnet)
- [Lightning Network Matrix Chat](https://matrix.to/#/#btcln:matrix.org)
- [r/lightningnetwork Subreddit](https://www.reddit.com/r/lightningnetwork/)
- [r/TheLightningNetwork Subreddit](https://www.reddit.com/r/TheLightningNetwork/)
- [Rings of Fire Telegram Group](https://t.me/theRingsOfFire)
- [Rings of Fire GitHub Wiki](https://github.com/Rings-of-Fire/ring-of-fire/wiki)
- [Reddit Liquidity Swaps Thread](https://www.reddit.com/r/TheLightningNetwork/search?sort=new&restrict_sr=on&q=flair%3ALiquidity%2BSwaps)

## Watchtowers

- [The Eye of Satoshi: Rust-based Watchtower Implementation](https://github.com/talaia-labs/rust-teos)
- [LND Watchtower: Built-in Watchtower Functionality](https://docs.lightning.engineering/lightning-network-tools/lnd/watchtower)

## Mempool Resources

- [Mempool.space: Real-Time Bitcoin Mempool Visualizer](https://mempool.space/)
- [Bitcoin Explorer: Detailed Transaction and Block Explorer](https://bitcoinexplorer.org/)
- [Johoe's Bitcoin Mempool Statistics: Historical Mempool Data](https://jochen-hoenicke.de/queue/#BTC,24h,weight)
- [TX Street: Visual Bitcoin and Ethereum Transaction Monitor](https://txstreet.com/v/btc)

## Educational Resources

- [Lightning Curriculum by Chaincode Labs: Comprehensive Learning Path](https://github.com/chaincodelabs/lightning-curriculum)
- [Mastering the Lightning Network: Open-Source Book](https://github.com/lnbook/lnbook)
- [Professional Lightning Network Node Rebalancing Tutorial](https://www.youtube.com/watch?v=0r3Th42zfDk)
- [Comprehensive Bitcoin Lightning Network Node Setup Tutorial](https://www.youtube.com/watch?v=KItleddMYFU)
- [T-bast's Lightning Network Documentation](https://github.com/t-bast/lightning-docs)
- [Interactive Lightning Network Workshop](https://github.com/roeierez/lightning-workshop)
- [Cyberhub's Lightning Network Resources](https://cyberhubnode.notion.site/cyberhubnode/Cyberhub-Home-34858179510a44

## Network Statistics

- [1ML.com Lightning Network Statistics](https://1ml.com/statistics)
- [Bitcoin Visuals - Lightning Network Metrics](https://bitcoinvisuals.com/lightning)

## Further Reading

- [Diamond Hands Lightning Network Routing Report](https://medium.com/@coin_and_peace/diamond-hands-lightning-routing-report-jan-2022-85733104fa8d)
- [Jameson Lopp's Comprehensive Lightning Network Resource Collection](https://www.lopp.net/lightning-information.html)
- [Lightning Landscape: Overview of Lightning Network Projects](https://www.lightning-landscape.net)
- [LND Security Case Study: Recovering Funds from a Hacked Node](https://medium.com/@goryachev/bitcoin-node-security-case-study-e1ca00a378b5)

## Related Resources

To explore other aspects of the Bitcoin and freedom tech ecosystem, check out these additional resource directories:

- [DLC.wiki](https://www.dlc.wiki): Everything you need to know about Discreet Log Contracts (DLCs), an innovative Bitcoin smart contract technology.
- [Nostr.net](https://www.nostr.net): A complete guide to Nostr (Notes and Other Stuff Transmitted by Relays), including projects, implementations, and resources.
- [Ungovernable.tech](https://ungovernable.tech): A curated collection of resources on encryption, privacy tools, and decentralized technologies.

## Contributing

If you'd like to add something to this list, please submit a [Pull Request on GitHub](https://github.com/aljazceru/lightning-network.tech).

This resource guide is maintained by [@aaaljaz](https://twitter.com/aaaljaz) | [aljaz@nostr.si](https://nostr.at/npub1aljazgxlpnpfp7n5sunlk3dvfp72456x6nezjw4sd850q879rxqsthg9jp). Your contributions help keep this information up-to-date and valuable for the Lightning Network community.