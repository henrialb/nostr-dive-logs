# Nostr Dive Logs

This repo is a work in progress to build a NIP[^1] specification allowing dive logbooks on Nostr. The main goal is to produce a NIP draft. I also aim to make available example code and a reference implementation.

- [NIP draft](NIP-draft.md)
- Example code
- Reference client

If you're unfamiliar with the Nostr protocol, learn about it [here](https://nostr.how/).

## Motivation

Divers rely on applications developed by the main dive organisations for their digital logbook. This means they don't own their data (as they do with a physical logbook) and can't easily migrate to another application. Having a NIP specification for dive logs would allow multiple interoperable clients to be developed. Divers can choose their favourite logbook application and switch any time, taking their dive history with them. This is possible thanks to Nostr's decentralised, permissionless and censorship-resistant nature. Additionally, social components can be integrated, allowing divers to share a dive with the world and other users to see a public dive, comment and zap it (give a tip).

## Possibilities

- Divers can log their dives, which can be private or public
- Divers can attach media to their dives (photos, videos)
- Divers can review sites and dive centres
- Dive centres/schools can verify dives
- Dive organisations such as PADI and SSI can accredit dive centres
- Dive schools can issue certificates to divers
- Dive centres can verify a diver's certification
- I'm sure there's more...

## Contribute

The easiest way to contribute is giving feedback. Ideas and code are welcome too.

[^1]: NIPs stand for Nostr Implementation Possibilities
