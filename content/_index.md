+++
title = "Civkit"
description = "Civkit Overview"
+++

# Civkit

The Civ Kit combines the Nostr architecture with the Lightning Network, prioritizing “privacy and security through escrowed trades, decentralized identity, moderation, a P2P messaging protocol, and know-your-peer (KYP) oracles for adjudication,” The system aims to support all kinds of trading, including goods and services.

## Civkit Node

The CivKit Node represents an experimental NIP-01 Rust relay, complemented by ongoing development of communication gateways for BOLT8 Noise transport and BOLT4 sphinx onion routing. Alongside this, there is a companion client binary designed specifically for development and testing purposes.

## Staking Credentials

Rust-based framework implements a reputation system aimed at enhancing the resilience of the Lightning Network against channel jamming. Central to this system is the innovative use of "credentials" issued by network routing hops, attached to each Hashed Time-Locked Contract (HTLC) forward request. These credentials are crucial for a reputation algorithm that rewards or penalizes payment senders, promoting efficient channel liquidity management. 