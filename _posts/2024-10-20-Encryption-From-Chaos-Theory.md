---
title: "A twist on standard encryption"
date: 2024-10-20 16:33:00 +0100
categories: [Computer Science, projects]
tags: [encryption, CS,projects]
---
Here's a recent take on standard encryption I've recently had. What if we used the principles of chaos theory to be the backbone of encryption. Due to chaos' theory's  unique sensitivity to the initial conditions in a system and its unpredictability, it poses as a credible candidate to further enhancing the world's current methods of encryption, perhaps even providing for a neat alternative solution.

More formally here is a project that i am keen to start working on: 
> Chaos-Based Encryption System : A novel based encprytion system based on chaotic systems.

Loose plan: It's gonna take the predefined chaotic systems (perhaps one ,perhaps multiple)  with their own initial values and control parameters and use that to generate a pseudo-random sequence. That sequence will be our  **chaotic key**. We will then use the **chaotic key** to encrypt the users's plain text via the [XOR](https://en.wikipedia.org/wiki/XOR_gate#:~:text=XOR%20represents%20the%20inequality%20function,the%20other%20but%20not%20both%22.) function. We will then use the **chaotic key** to decrypt the plaintext.
