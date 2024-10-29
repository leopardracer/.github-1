![StoryProtocol](https://miro.medium.com/v2/resize:fit:1400/1*9-kKzLsQR1CRmbZfQboA6g.jpeg)

Story Protocol is building the Programmable IP layer to bring programmability to IP.
Story Protocol transforms IPs into networks that transcend mediums and platforms, unleashing global creativity and liquidity.

[![X](https://img.shields.io/badge/-Twitter-blue?style=flat&logo=X)](https://x.com/storyprotocol?s=21&t=bPOi8G8ajYBA3bYP6hS98Q)
[![Discord](https://img.shields.io/badge/-Discord-blueviolet?style=flat&logo=Discord)](https://discord.gg/storyprotocol)
[![Jobs](https://img.shields.io/badge/-Jobs-brown?style=flat&logo=W)](https://jobs.lever.co/storyprotocol)
[![Website](https://img.shields.io/badge/-Website-yellow?style=flat&logo=)](https://www.story.foundation)
[![Docs](https://img.shields.io/badge/-Docs-white?style=flat&logo=)](https://docs.story.foundation/docs/what-is-story)
[![Explorer](https://img.shields.io/badge/-Explorer-orange?style=flat&logo=)](http://explorer.story.foundation)


# 🔍 Overview

Story's "Proof-of-Creativity" protocol introduces a revolutionary open Programmable IP layer, elevating IP to a first-class entity in the blockchain ecosystem. At the heart of this system is the [🧩 IP Asset](https://docs.story.foundation/docs/ip-asset) and its associated [⚙️ IP Account](https://docs.story.foundation/docs/ip-account), a smart contract designed to serve as the core identity for each IP. This account-centric approach enables the storage and management of IP-related data, as well as the execution of diverse functions to manipulate that data via [🧱 Modules](https://docs.story.foundation/docs/story-modules).

# Architecture
![Architecture](https://files.readme.io/251dabc-story-v1-architecture.png)

Let's briefly introduce the layers mentioned in the above diagram:

# 🧩 IP Asset
An IP Asset is an on-chain NFT, which represents an IP. If your IP is already on-chain (like an Azuki or Pudgy Penguin), it is already ready to be registered on Story. If your IP is off-chain, you would simply mint an NFT to represent it and then register it as an IP Asset on Story.

Upon registering an NFT as an IP Asset, an associated IP Account is created.

# ⚙️ IP Account
IP Accounts are smart contracts that are tied to an IP Asset, and do two main things:

Store its associated IP Asset's data (such as the associated License Tokens and Royalty Tokens) created from an IP
Facilitates the utilization of this data by various modules. For example, licensing, revenue/royalty sharing, remixing, and other critical features are made possible due to the IP Account's programmability.

# 🧱 Modules
Modules are customizable smart contracts that define and extend the functionality of IP Accounts. Modules empower developers to create functions and interactions for each IP to make IPs truly programmable.

We already have a few core modules:

1. 📜 Licensing Module
2. 💸 Royalty Module
3. ❌ Dispute Module
4. 👥 Grouping Module

# 🗂️ Registry
The various registries on Story function as a primary directory/storage for the global states of the protocol. Unlike IP Accounts, which manage the state of specific IPs, a registry oversees the broader states of the protocol.

# 💊 Programmable IP License (PIL)
The PIL is a real, off-chain legal contract that defines certain License Terms for how an IP Asset can be legally licensed. For example, how an IP Asset is commercialized or remixed, and who is allowed to do that and under what conditions.

We have mapped these same terms on-chain so you can easily attach terms to your IP Asset for others to seamlessly and transparently license your IP.
