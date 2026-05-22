# Web2 QR vs Web3 QR: Architectural Differences

> From Address References to Executable Transaction Instructions

This document focuses on architectural concepts rather than production implementations.
---

## Overview

This repository explores architectural differences between traditional QR payment systems and distributed transaction execution.

---

## Architecture

## Why This Difference Matters

Traditional QR systems typically treat QR codes as identifiers.

The QR itself does not define the transaction.

Execution occurs after server interpretation.

```text
Web2

QR
↓

Lookup
↓

Server Decision
↓

Transaction
```

In distributed transaction environments, the QR may carry enough context to reconstruct execution intent.

```text
Web3

QR
↓

Instruction Decode
↓

Verification
↓

Execution
```

The architectural shift is not simply decentralization.

It is a change in the role of QR itself.

```

## Documents

- [QR Evolution](docs/qr-overview.md)

- [Web2 Architecture](docs/web2-architecture.md)

- [Web3 Architecture](docs/web3-architecture.md)

---

## License

MIT
