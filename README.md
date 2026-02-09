# Libertas

Libertas is a **fast, reliable, and fully decentralized proof-of-work cryptocurrency** designed with simplicity, security, and accessibility in mind.

Unlike many modern coins that chase complex features, Libertas focuses on a clean, deterministic, and modular architecture that ensures long-term stability and usability. 

Its ecosystem combines hybrid CPU/GPU mining, cross-platform wallets (Windows, Linux and Android), deterministic cryptography, and a decentralized peer-to-peer network of nodes.

---

## Overview

Libertas aims to be a cryptocurrency that works **for everyone**: 

* Miners

* Developers

* Users

By prioritizing **Efficiency and modular design**:

Libertas achieves compatibility across platforms while maintaining a fully decentralized network.

The core design philosophy is simple:

- **Permissionless:** Not proof-of-stake, not centralized.
- **Minimalism:** Unnecessary features that make chain slower and less secure are not implemented.
- **Accessibility:** Anyone can participate in mining and node operation. Supports both GPUs and CPUs.
- **Efficiency:** GPU mining accelerates performance without breaking the chain consistency.
- **Reliability:** Deterministic cryptography, cross-platform wallets, and robust P2P networking ensure predictable behavior.
- **Developer-Friendliness:** Modular, open-source libraries allow experimentation and integration.

Libertas does **NOT** include smart contracts, NFTs, token systems, or experimental consensus mechanisms. 

This intentional **minimalism** ensures a stable foundation for users and developers alike.

---

## Core Components

### 1. Mining

Libertas implements BLAKE3 **proof-of-work mining**:

- **CPU Mining:** Out-of-the-box functionality allows anyone to mine on standard hardware efficienctly
- **GPU Mining:** OpenCL acceleration allows higher speed for miners.
- Mining rewards are distributed fairly and deterministically, without centralization risks.

The hybrid design ensures **wide accessibility** while still rewarding more capable hardware without compromising fairness.

---

### 2. Wallets

Libertas provides **cross-platform wallets**:

- **Desktop:** Qt GUI, supports both Windows and Linux.
- **Mobile:** Android app built with C++ core (NDK) and Kotlin GUI wrapper.
- **CLI:** Full-featured command-line wallet.

Wallets are deterministic and interoperable:

- 12-word mnemonic recovery **compatible across all platforms**.
- **Deterministic cryptography** ensures identical addresses and balances across devices.

This guarantees that users can safely restore wallets and transact anywhere.

---

### 3. Cryptography

Libertas relies on **proven, modern cryptography**:

- **BLAKE3**: fast, secure hash function for block hashing, transaction integrity, and Merkle tree construction.
- **Libsodium**: for key generation and secure memory.
- Deterministic key derivation ensures cross-platform compatibility and reliability.

This cryptographic foundation is designed to minimize risk and maximize predictability for both developers and users.

---

### 4. Peer-to-Peer Network

Libertas operates on a **fully decentralized P2P network**:

- **Automatic node discovery** ensures nodes find peers without central servers.
- **Chain synchronization from genesis** allows new nodes to catch up securely.
- **Transaction and block validation** enforces network-wide consensus and prevents invalid data propagation.
- Network layer designed for robustness, including handling node churn and forks.

The combination of a deterministic blockchain and a reliable P2P layer ensures a strong foundation for decentralized operation.

---

## Ecosystem Philosophy

Libertas emphasizes **clarity and trust** over hype:

- **Minimalism:** No fads like smart contracts, token schemes, or experimental consensus features.
- **Predictability:** Deterministic wallets, hashing, and block layout prevent inconsistencies across platforms.
- **Accessibility:** Hybrid mining and cross-platform nodes allow anyone to participate.
- **Developer-Focused:** Modular design enables experimentation and integration into other projects.

This approach contrasts with coins that prioritize flashy features over reliability, giving Libertas a unique position as a **stable, understandable, and usable cryptocurrency**.

---

## Target Audience

Libertas naturally appeals to:

1. **Small scale miners** — CPU and GPU mining accessible from day one without needing ASICs.
2. **Developers and researchers** — clean, modular code for experimentation and learning.
3. **Users seeking stability** — predictable wallets and cross-platform compatibility.
4. **Community-oriented participants** — fully decentralized P2P network without central servers.

By focusing on these groups, Libertas fills a niche of **transparent, reliable, and developer-friendly cryptocurrency**.

---

## Technical Design Highlights

- **Modular Architecture:** Mining, wallet, and node functionalities are separated into reusable libraries. 
- **Cross-Platform Support:** CLI core and QT wallets are supported in both Windows and Linux. Android Has its own wallet with kotlin and C++.
- **Secure Wallets:** Wallets rely on libsodium for KDFs, signatures, and memory safety.
- **Robust Networking:** P2P protocol includes discovery, validation, and resynchronization mechanisms to maintain network integrity.

---

## Vision

Libertas is designed to be **a reliable foundation** rather than a flashy platform. 

It prioritizes **predictable behavior, accessibility, and developer usability**, forming a strong base for miners, developers, and anyone seeking a decentralized digital currency that “just works.”.

Future growth can focus on **community adoption, developer experimentation, and ecosystem stability**, rather than chasing trends that complicate the protocol or compromise reliability.

---

## License

MIT LICENSE

## Donations:

btc: bc1qxawtsayllp5cqszn63w47qmpnhh42pu35cd5dl
usdt: 0xA3b26534a678eacB61b6277f9EB6A0EB5effEA3a 
xmr: 8Bz7dQWhmmtRCMqi5gXszx2LDS7gJtxg9XiCpANVnJxZea3iaJzH2w22aBVGwgR1PW5a2PDB1V8JAhcVG7NKedM4P4HPT4V
doge: DKEUsAJ9dchxPAFa7Stf3U9tWzEYzzYmgC
ltc: ltc1qlahavrs3rvlpn2ydxle9x6v4fthlq5whzyj7fu
xrp: rsuHRQh6Gn246oi2ynDHJ15i9TJSaYp8NQ
eth: 0xA3b26534a678eacB61b6277f9EB6A0EB5effEA3a
sol: EFNUD7SCSagUxNkJdnN8K7dNoKyqv7zbioDusinQTNZP
