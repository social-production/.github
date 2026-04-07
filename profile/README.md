# Social Production

Build production for use, not profit.

Social Production is an open source platform for communities that want to organize collective production, governance, funding, and distribution outside market relations.

It is meant to help people build real projects together, pool resources transparently, govern decisions collectively, and distribute what gets produced by need instead of exchange.

## New Here

If you landed here from a QR code, sticker, or shared image, start with the pitch page and then the contributor guide.

- Start with the public pitch: [planning/OUTREACH/PITCH_PAGE.md](https://github.com/social-production/planning/blob/main/OUTREACH/PITCH_PAGE.md)
- Read the contributor guide: [planning/CONTRIBUTOR_GUIDE.md](https://github.com/social-production/planning/blob/main/CONTRIBUTOR_GUIDE.md)
- See current priorities: [planning/CURRENTLY_WORKING_ON.md](https://github.com/social-production/planning/blob/main/CURRENTLY_WORKING_ON.md)

## What This Solves

Most platforms help people communicate. They do not help communities collectively produce what they need.

Social Production is aimed at communities that want to:

- organize real production such as food, housing, care, tools, repair, free software, etc. The sky is the limit.
- pool resources without turning them into private ownership claims
- make decisions transparently instead of through informal power
- track planning, funding, and distribution in one system
- reduce dependence on wages and markets over time

## How It Works

- People create projects around concrete needs and productive work.
- Members coordinate labor, resources, and distribution together.
- Governance, funding, and other key records are intended to be transparent and on-chain.
- The legal and stewardship model is being developed in public, with the current direction centered on non-profit asset stewardship rather than private ownership.
- The current architecture direction uses local-first applications where every app instance runs as a node, with the app UI talking to its own local node runtime while nodes sync with each other over the peer-to-peer network.

## What Gets Built

Examples include:

- food production and distribution
- housing and maintenance projects
- care networks and mutual aid
- tool libraries and repair
- education, documentation, and free software
- shared infrastructure and other community needs

## Why This Platform

People can already use Discord, Telegram, Facebook groups, or other tools to discuss ideas.

Those tools do not give communities a shared structure for production planning, pooled resources, transparent governance, and need-based distribution. Social Production is being built specifically for that.

## Repositories

| Repo | Purpose |
|---|---|
| `planning` | Canonical product, architecture, legal, and outreach source-of-truth docs |
| `network` | Rust node, blockchain, sync, and terminal UI track |
| `app` | Lead Flutter application track |
| `web` | Older prototype and reference material, not the lead product track |
| `assets` | Logos, icons, and reusable visual assets |
| `proto` | Protobuf and gRPC contract workspace|
| `migrations` | Migration and projection-schema workspace |
| `accounting` | Separate support workspace, not the first-stop contributor track |

## Project Status

The project is still early, this is not yet a production-ready network for real communities.

Current needs:

- Rust and distributed systems
- Flutter and application development
- planning and documentation
- design and outreach
- legal and governance research
- real-world production and organizing experience

## Quick Start By Role

- Developers: start with the [contributor guide](https://github.com/social-production/planning/blob/main/CONTRIBUTOR_GUIDE.md), then follow the [network](https://github.com/social-production/network) or [app](https://github.com/social-production/app) track that fits your skills.
- Designers and outreach contributors: use the [pitch page](https://github.com/social-production/planning/blob/main/OUTREACH/PITCH_PAGE.md), browse the [outreach folder](https://github.com/social-production/planning/tree/main/OUTREACH), and use the [assets repo](https://github.com/social-production/assets). There are already shareable materials there, or you can make your own.
- Organizers and governance researchers: use the [pitch page](https://github.com/social-production/planning/blob/main/OUTREACH/PITCH_PAGE.md) and the [drafts folder](https://github.com/social-production/planning/tree/main/DRAFTS).

If you want to contribute, start with the contributor guide and then pick one focused item from the current working list.