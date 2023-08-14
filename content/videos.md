+++
title = "Videos"
description = "Here are some videos I've done."
date = "13 Aug. 2023"
aliases = ["videos"]
author = "Severiano Sisneros"
+++

## Devcon VI - A SNARKs Tale
> We tell the story of deploying a real-world solution using SNARKs as a core primitive; highlighting many cutting edge SNARKs and their limitations in the hope to identify opportunities for the community to make Ethereum more SNARK friendly, creating a diverse ecosystem where SNARKs built upon a variety of unique primitives can thrive.

{{< youtube GnYM9yxIRSs >}}

This talk was a high level (light on technical details) description of some our research into various SNARK constructions while designing and building a high-throughput one-way payment channel solution to enable query payments for indexers in The Graph protocol. We looked at several cutting edge SNARKs and also Homomorphic Signatures. In the end, all the verification for all these methods where too high to justify, we ended up engineering a much simpler (cryptographically) system using only standard ECC. The solution is called [TAP](https://github.com/semiotic-ai/timeline-aggregation-protocol) and is currently being integrated into The Graph.

## zkOps: The Future of Zero Knowledge Deployment Tools Panel by Aaron Greenblatt
>"There is great excitement surrounding the potential applications for newly-introduced zero knowledge (zk) proof systems. However, today, there are barriers to mass adoption of zk verifiable computing: zk proof generation involves many end-user mathematical choices; is computationally intense, and; leverages a wide array of software languages and libraries. Accordingly, widespread adoption of zk will require additional practical, operational infrastructure. We call this infrastructure zkOps.
>
>Join us for a panel discussion on current zk development and deployment strategies and on future avenues for zkOps tooling. Since both zk proofs and many Web2 workloads fundamentally rely on computation, there are parallels between existing Web2 devops infrastructure and future zkOps tools; we compare and contrast these techniques during this discussion. Our goal in this talk is to engage with the developer community to build consensus around future zkOps infrastructure priorities."

{{< youtube xBp0NpuQ8IY >}}

This was a panel I participated in at ETHDenver 2023.