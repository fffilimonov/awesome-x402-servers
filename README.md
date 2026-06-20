# Awesome x402 Servers

Awesome Servers with x402 Payment Protocol Integration

> 📅 Updated for June 2025 release of x402 Whitepaper and Protocol Specs

---

## 📄 What is x402?

x402 is an open payment protocol built on top of HTTP using the long-reserved `402 Payment Required` status code. It enables AI agents, clients, and web services to conduct **autonomous pay-per-use payments** using stablecoins such as USDC on EVM-compatible blockchains.

It allows seamless machine-native transactions:

* No API keys
* No subscriptions
* No accounts
* No chargebacks
* Instant payments

**Read the full [x402 Whitepaper](https://x402.org)**

---

## 📁 Community Servers

* wrapper-agency - 8 pay-per-call utility API servers settled in USDC on Base via x402 (free tier + one shared key): historical FX rates, color conversion, timezone/DST, mock data, cron explainer, QR codes, data-format conversion, encode/hash. [Website](https://fx.wrapper-agency.com) [Github](https://github.com/Neta08-svg/historical-fx-rates)
* Proxy402 - Monetize any link in seconds. [Website](https://proxy402.com) [Github](https://github.com/Fewsats/proxy402)

---

## Dashboard

* Base Mainnet Charts by programmer [Dune Analytics](https://dune.com/programmer/x402-base-mainnet)
* x402 @lifewillbeokay [Dune Analytics](https://dune.com/lifewillbeokay/x402)


## Demos / Talks

* x402: Building dynamic tools for AI agents, demos, and use-cases. [Youtube](https://www.youtube.com/watch?v=pL5LxhZ8iCY&t=1744s) 
* x402: Internet Native Payments for Humans and AI Agents. [Youtube](https://www.youtube.com/watch?v=_APaEVnyNWE)

---

## 📅 Supported Schemes

* **exact** (current): Uses EIP-3009 (`transferWithAuthorization`)
* **permit** (experimental): Uses EIP-2612 (`permit`) — enables streaming / usage-based payments via routing contracts.
* Future: Hybrid escrow-based settlement and multicall batching.

---

## 💪 Why x402?

* Built for **agentic commerce**
* Instant micropayments (\$0.001 per request possible)
* Supports AI agents, APIs, content paywalls, cloud compute, etc.
* No subscriptions, no API keys, no manual billing

---

## 🔎 Further Reading

* [x402 Whitepaper (May 2025)](https://x402.org)
* [EIP-3009 Spec](https://eips.ethereum.org/EIPS/eip-3009)
* [Docs](https://x402.gitbook.io/)
---

## 📗 Community

* [Reddit x402](https://www.reddit.com/r/x402)
* [Discord - Coinbase Developer Platform](https://discord.gg/invite/cdp)
* [GitHub - x402](https://github.com/coinbase/x402)
