# Rutero (RUTR) - Solana Utility Token

**Empowering delivery drivers and gig workers across Latin America**

---

## Overview

Rutero (RUTR) is a Solana-based utility token designed to support delivery drivers and gig workers throughout Latin America. The project enables:

- **Fair Rewards**: Transparent compensation system for drivers
- **Fuel Benefits**: Token-based fuel subsidy program
- **On-Chain Identity**: Verifiable reputation and work history
- **Community Governance**: Democratic decision-making for ecosystem growth

---

## Token Details

| Property | Value |
|----------|-------|
| **Name** | Rutero |
| **Symbol** | RUTR |
| **Network** | Solana |
| **Standard** | SPL Token |
| **Creator Address** | `GqniF5QBtNG4W2e9dghw5q1TK6taQDJrKPnnTZR1WmU4` |

---

## Metadata

This repository contains the official Metaplex metadata for the RUTR token.

### Files
- `metadata.json` - On-chain metadata following Metaplex Token Standard

### Image
![Rutero Logo](https://i.ibb.co/ynwRvdvk/Screenshot-2025-11-23-at-8-58-08-AM.png)

---

## Links

- **Website**: [Rutero on Notion](https://www.notion.so/Rutero-RUTR-2c20acff37d28006ac53e6c2c42fb0db)
- **Whitepaper**: [RUTERO Whitepaper v1](https://www.notion.so/RUTERO-RUTR-WHITEPAPER-v1-2c20acff37d2808fb839c0e92652443b)
- **Twitter/X**: [@ruterorutr](https://x.com/ruterorutr)
- **Telegram**: [@rutero_rutr](https://t.me/rutero_rutr)

---

## Roadmap

### Phase 1: Token Launch
- [x] Token creation on Solana
- [x] Metadata deployment
- [x] Community channels setup
- [x] Whitepaper publication

### Phase 2: Utility Development
- [ ] Driver registration system
- [ ] Rewards distribution mechanism
- [ ] Fuel partner integrations
- [ ] Mobile wallet integration

### Phase 3: Ecosystem Growth
- [ ] Governance token implementation
- [ ] Staking mechanisms
- [ ] Cross-chain bridges
- [ ] Regional expansion

---

## Technical Implementation

### Solana Program
The token is built on Solana's SPL Token program, ensuring:
- Fast transactions (~400ms finality)
- Low fees (<$0.01 per transaction)
- High throughput (65,000+ TPS)

### Metadata Standard
Follows [Metaplex Token Metadata](https://docs.metaplex.com/programs/token-metadata/) standard for compatibility with:
- Solana wallets
- NFT marketplaces
- Portfolio trackers

---

## For Developers

### Update Metadata
```bash
# Install Solana CLI
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"

# Install Metaplex Token Metadata CLI
cargo install spl-token-metadata

# Update metadata (requires creator wallet)
spl-token-metadata update <TOKEN_MINT> metadata.json
```

### Verify On-Chain Data
```bash
# Check token info
spl-token supply <TOKEN_MINT>

# Verify metadata
solana account <METADATA_ACCOUNT>
```

---

## Community

Join our growing community of drivers and supporters:

- **Twitter**: Daily updates and announcements
- **Telegram**: Direct community support and discussion
- **Notion**: Documentation and roadmap details

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with the vision of creating fair opportunities for gig workers in Latin America.*
