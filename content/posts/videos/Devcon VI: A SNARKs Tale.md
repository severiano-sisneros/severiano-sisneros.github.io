---
title: "Devcon VI: A SNARKs Tale"
date: 2023-08-13T19:45:46-07:00
tags: [Video, Cryptography]
draft: false
---
This talk was a high level, light on technical detail, description of some our research into various SNARK constructions while designing and building a high-throughput one-way payment channel solution to enable query payments for indexers in The Graph protocol. We looked at several cutting edge SNARKs and also Homomorphic Signatures. In the end, all the verification for all these methods where too high to justify, we ended up engineering a much simpler (cryptographically) system using only standard ECC. The solution is called [TAP](https://github.com/semiotic-ai/timeline-aggregation-protocol) and is currently being integrated into The Graph.

{{< youtube GnYM9yxIRSs >}}
> We tell the story of deploying a real-world solution using SNARKs as a core primitive; highlighting many cutting edge SNARKs and their limitations in the hope to identify opportunities for the community to make Ethereum more SNARK friendly, creating a diverse ecosystem where SNARKs built upon a variety of unique primitives can thrive.
