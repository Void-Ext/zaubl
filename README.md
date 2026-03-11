# Zaubl 🧭
**Search is dead. Zaubl instead.**

## Those who search are lost. On Nostr, we navigate.
The Nostr protocol is a massive, uncharted ocean of data. If you are relying on basic NIP-50 keyword matching, you are drowning in chronological noise and botnet spam. You don't need a search bar. You need a navigator.

**Zaubl** is the first true signal-weighted ranking engine built specifically for the Nostr network. 

🔗 **[Access the Live Engine: Zaubl.com](https://zaubl.com)**

---

## What is Zaubl?
This repository serves as the public documentation for the Zaubl engine. While the core codebase remains proprietary infrastructure for the Aubl-Verse, the engine is actively processing the global Nostr firehose in real-time.

Instead of raw keyword indexing (like a glorified Ctrl+F), Zaubl operates on a multi-process ranking algorithm designed to separate signal from noise:

* **The Siphon:** Ingests the raw, unfiltered global feed directly from the relays (The Ore).
* **The Refiner:** Calculates the cryptographic weight and true community value of interactions, such as zaps, reposts, and replies (The Amperage).
* **The Foundry:** Ranks the results based on quality, ensuring the botnet spam sinks and the highest-signal content rises to the top (The Metals).

## Architecture & Build
Zaubl is a multi-process Node.js engine running on sovereign architecture, featuring:
* Real-time WebSocket ingestion of global Nostr relays.
* Asynchronous data processing and cryptographic weight calculations.
* A high-speed, decoupled delivery layer engineered for zero-downtime failover.

## About the Project
Zaubl was architected and built from the ground up to solve the hardest problem on decentralized networks: data curation without centralized censorship. It is the flagship search utility of the Aubl-Verse ecosystem.

**Status:** Active Production  
**Developer:** [Void-Ext]  
**Website:** [zaubl.com](https://zaubl.com)
