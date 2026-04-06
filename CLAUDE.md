# librtbit-dht

Kademlia DHT implementation for the rtbit BitTorrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-buffers** (git, v0.1.0)
- **librtbit-bencode** (git, v0.1.0)
- **librtbit-clone-to-owned** (git, v0.1.0)
- **librtbit-core** (git, v0.1.0)
- **librtbit-sha1-wrapper** (git, v0.1.0)

## Features

- `sha1-crypto-hash` (default) — uses crypto-hash
- `sha1-ring` — uses aws-lc-rs

## BEP Implementations

- BEP 5 — Full Kademlia DHT protocol
- BEP 44 — Mutable DHT items with Ed25519 signatures
