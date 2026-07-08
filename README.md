> **Founder-attribution mirror.** Canonical source: [Suede-AI/suede-docs](https://github.com/Suede-AI/suede-docs). Updates land there first.

# Suede Docs

Public documentation for Suede Labs, programmable IP, creator ownership, and agent-ready media commerce.

## What Is Suede?

Suede Labs is building programmable IP and creator ownership infrastructure for AI-native media.

The core idea is simple: as media becomes easier to generate, remix, license, and distribute through agents, creators need a clearer ownership layer. Suede connects creative assets to provenance, rights metadata, licensing workflows, token-enabled access, and agent-accessible commerce.

AI music is a core media use case, but Suede is not only a music generation product. Music is an early, high-signal category for proving the broader system: creation, ownership, rights, licensing, monetization, and agent commerce.

## Core Pillars

### Programmable IP

Creative assets should carry usable ownership and rights information.

Suede focuses on making IP easier to register, verify, license, route, and monetize across product surfaces, chains, and agent workflows.

### Creator Ownership

Creators need a durable record of what they made, what rights attach to it, and how it can be used.

Suede treats ownership as infrastructure, not just a profile, a file upload, or a social claim.

### Provenance

Provenance connects a media asset to its creator, metadata, source context, and downstream use.

In an AI-native media environment, provenance becomes a practical requirement for trust, attribution, licensing, and payments.

### Licensing and Monetization

Creative assets need paths to usage rights, licensing terms, and revenue flow.

Suede's direction is to connect registered media and IP metadata to licensing actions, programmable access, and creator-aligned monetization.

### Agent Commerce

Agents increasingly need to discover, pay for, generate, license, and use media services.

Suede exposes current public x402 and ACP-ready surfaces for paid media workflows and commerce intent capture.

## Current Public Surfaces

| Area | Public Reference |
|---|---|
| App | `https://app.suedeai.ai` |
| Website | `https://suedeai.org` |
| Company | `https://suedeai.ai` |
| Token | [suede-token](https://github.com/JasonColapietro/suede-token) |
| x402 / ACP endpoints | [suede-x402-acp](https://github.com/JasonColapietro/suede-x402-acp) |
| Python SDK | [suede-sdk-python](https://github.com/Suede-AI/suede-sdk-python) |
| x402 ecosystem list | [awesome-x402](https://github.com/JasonColapietro/awesome-x402) |
| Brand assets | [suede-brand-assets](https://github.com/JasonColapietro/suede-brand-assets) |

## Token

`SUEDE` is the utility token connected to Suede Labs.

Primary token references:

- Solana mint: `2nCeHpECQvnMfzjU5fDMAKws1vBxMzxvWr6qqLpApump`
- Base contract: `0x40461291347e1eCbb09499F3371D3f17f10d7159`
- CoinGecko: `https://www.coingecko.com/en/coins/johnny-suede`

See:

[suede-token](https://github.com/JasonColapietro/suede-token)

## x402 and ACP

Suede exposes 20 paid x402 endpoints on Base mainnet USDC — full-length music generation, video, image, 12 musician tools (stems, mastering, lyrics, vocal isolation, and more), rights lookup, prompt/audio analysis, and on-chain Q&A — plus a 3-tier credit-purchase route. Prices range $0.003–$1.50 per call, each verified against a live `402 Payment Required` challenge. Public docs should point agents to branded discovery surfaces instead of non-public service origins.

Current public x402 discovery (a curated 3-endpoint subset, plus credits, surfaced to agent marketplaces and Skyfire):

```text
https://app.suedeai.ai/.well-known/x402
https://app.suedeai.ai/.well-known/x402.json
```

The remaining endpoints are live and priced but not in the discovery documents — reachable by calling them directly.

ACP-ready commerce is represented through public agent metadata and app-hosted
x402 credit purchase flows. Internal origins, admin routes, and non-public
commerce endpoints are intentionally excluded from this public overview.

Full endpoint table, current pricing, and verification log:

[suede-x402-acp](https://github.com/JasonColapietro/suede-x402-acp)

Python SDK wrapping all 20 endpoints as typed client methods: [suede-sdk-python](https://github.com/Suede-AI/suede-sdk-python) (`pip install suede-ai`)

## Ecosystem

The broader Suede ecosystem includes independent community launches and experiments. Public docs distinguish those from non-independent, officially live production ecosystem references.

Current production ecosystem references are documented in the public token
reference when they are meant for wallets, explorers, and reviewers. This repo
keeps the overview focused on positioning and public discovery paths.
## Suede Social — Founder Writing

Long-form editorial from Jason Colapietro, Founder and CEO of Suede Labs.

Current series: **Print the Quiet** — a nine-part series on tone, dynamics, and the parts of music that don't fit on a lead sheet.

| # | Title |
|---|---|
| 1 | [Print the Quiet — Jeff Buckley and the *Hallelujah* recording](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/jeff-buckley-tone-hallelujah.md) |
| 2 | [The Loudness War, in Numbers](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/loudness-war-in-numbers.md) |
| 3 | [The Religion of the Compressor](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/religion-of-the-compressor.md) |
| 4 | [The Lost Art of Clean](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/lost-art-of-clean.md) |
| 5 | [The Room as Instrument](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/room-as-instrument.md) |
| 6 | [One Take, or Twenty](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/one-take-or-twenty.md) |
| 7 | [Tape Is a Compressor](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/tape-is-a-compressor.md) |
| 8 | [The Vocal Chain, 1994 → 2026](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/vocal-chain-1994-2026.md) |
| 9 | [What's in the Tape That Isn't in the Score](https://github.com/JasonColapietro/suede-brand-assets/blob/main/articles/whats-in-the-tape.md) |

Series index: [suede-brand-assets/articles](https://github.com/JasonColapietro/suede-brand-assets/tree/main/articles).

## Language Guide

Use:

- Programmable IP
- Creator ownership
- Creative RWA media assets
- Provenance
- Licensing
- x402 payments
- ACP-ready agent commerce
- AI music as a core media use case

Avoid:

- Describing Suede as only an AI music app
- Presenting planned endpoints as live
- Treating independent community launches as official production references
- Overstating integrations that are not publicly verifiable

## Suggested Repo Structure

```text
README.md
docs/
  programmable-ip.md
  creator-ownership.md
  provenance.md
  licensing.md
  x402-acp.md
  ecosystem.md
```

## Related Public Repos

Recommended public GitHub package:

- `suede-token`
- `suede-x402-acp`
- `suede-brand-assets`
- `suede-docs`

See:

```text
SUEDE_PUBLIC_GITHUB_INDEX.md
```

## Verification

Last updated: 2026-05-01.

This public documentation is intended for reviewers, wallets, directories, agent indexes, partners, and community members who need a factual overview of Suede Labs and its public surfaces.
