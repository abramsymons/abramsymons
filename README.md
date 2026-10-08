# Mahdi Heydari

Protocol engineer and security researcher. I design decentralized systems where **ordering is separated from execution**: replicas agree on a log, and each app replays it to reach the same state. I've applied that idea since 2018: BrightID's node consensus, the Muon oracle network, the Zellular sequencer, and the Zex exchange.

📍 Muscat, Oman · remote · open to protocol engineering and security research roles

📖 **[My story](https://abramsymons.github.io)** · 📄 **[Resume](https://abramsymons.github.io/resume.pdf)** ([detailed](https://abramsymons.github.io/resume-detailed.pdf))

## What I've built
Decentralized infrastructure as services that apps compose, so developers write only their own logic:

- **Consensus as a service**: [Zellular](https://github.com/zellular-xyz/zsequencer), a leader-based BFT sequencer run as an EigenLayer AVS, and now [vseq](https://github.com/abramsymons/firedancer/blob/vseq/src/app/vseq/DESIGN.md), Firedancer's Alpenglow consensus extracted as a standalone ordering service.
- **Custody as a service**: from the [pyfrost protocol spec](https://github.com/zellular-xyz/pyfrost/wiki/PyFrost-TSS-Protocol) to multi-chain custody (Bitcoin, EVM, Tron, Solana, Aptos) from one FROST validator group with a co-signing shield (ZexPorta).
- **Orderbook as a service**: [Zex](https://github.com/zex-fi), an exchange engine run as a replicated state machine. Prototyped at 100K orders/s, now heading to launch at about 1M orders/s with a C engine verified against the Python one.
- **Oracle as a service**: [Muon](https://muon.net), with three combinable security layers: threshold signatures (chosen over multisig in 2021), optimistic warrantors with collateral and disputes, and a co-signing shield.
- **Sybil-resistant identity**: primary architect of the [BrightID node](https://github.com/BrightID/BrightID-Node).
- **EigenLayer tooling**: lead author of [eigensdk-python](https://github.com/zellular-xyz/eigensdk-python) and co-built [eigensdk-js](https://github.com/zellular-xyz/eigensdk-js), the Python and JavaScript SDKs that won 🏆 1st place at EigenLayer AVS MicroHacks 2024.

## Security research
- **Aptos:** $30K bounty for a High-severity consensus bug that could halt the network.
- **Sui:** 8 denial-of-service reports, 4 reachable by unauthenticated peers.
- **Zex (internal audit):** contributed to the pre-launch security audit of the custody stack: threshold signing and multi-chain deposits.
- **Muon:** rogue-key and denial-of-service findings in the DKG.

## Writing
- [Threshold signatures, DKG, and attacks on complaint handling](https://github.com/zellular-xyz/pyfrost/wiki/PyFrost-TSS-Protocol)

📫 abramsymons@gmail.com · [X @0xmahdi_](https://x.com/0xmahdi_)
