# What is this course?

The Modern Zero Knowledge Cryptography IAP program surveys recent advancements in zero-knowledge cryptography over the last ten years, with a strong emphasis on their practical and user-facing applications.

Topics covered range from the mathematical foundations of modern zero-knowledge protocols (interactive protocols, elliptic curve cryptography, pairing-based cryptography, polynomial commitment schemes, zkSNARKs, and more) to practical constructions of digital systems enabled by ZK primitives (privacy-preserving identity and reputation systems, anonymous digital transaction systems, verifiable computation, and more). Towards the end of the course, students will implement their own “zero-knowledge circuits” that can be integrated into practical applications.

The focus of this course will be on developing a _conceptual understanding_ of modern zero-knowledge. As this four-week course is intended to be a survey of the “full-stack” landscape, from theory to application, less emphasis is placed on precise mathematical rigor, and more emphasis is placed on conveying the big picture ideas and methods that commonly appear in modern ZK applications.

The Modern ZK Crypto program has three components: lectures and workshops, optional (ungraded) problem sets and exercises, and an optional project component which interested students are highly encouraged to participate in.

  

*   [What is this course?](https://zkiap.com/#c6181ca6297f41a6a41216c596874efe)
*   [Lecture schedule & materials](https://zkiap.com/#34e5b6cf6e1d4dd3901940d4be2edb0b)
*   [Student Notes](https://zkiap.com/#556dec5a576849a9af1605f1b2d411db)
*   [Course Staff](https://zkiap.com/#0c43d6ee899d4231a7a041638402fe67)
*   [Prerequisites](https://zkiap.com/#b1d28c64d1ae4aaea40f89fae728ec72)
*   [Logistics](https://zkiap.com/#dba1d04223ae40fca8927c2f5d86bf48)
*   [Class components](https://zkiap.com/#d8c2ff6f72ed45bab66f5a5ef1b7db26)
*   [Recommended Project](https://zkiap.com/#772da2d1a38f48a0877cbf0ab20938a1)
*   [Optional Exercises and Problem Sets](https://zkiap.com/#4b6e58bf58284f8490ce6f3ec00614f8)

# Lecture schedule & materials

**Recordings, slides, notes, and exercises** are included in the dropdowns, updated after each session. Sessions are 90m each, held on **MWF from 2-3:30pm in 4-237** (with the exception of MLK day, when lecture is held on Tuesday instead).

  

‣

**Session 1 (Monday 1/9) Introduction to ZK** (Brian Gu)

We’ll give an overview of the course, and a whirlwind tour of modern zero-knowledge techniques and applications. This session will approach the “why” of the course: why has ZK been such an exciting topic lately, and why do we think that it has the potential to one of the biggest technology stories of the next decade?

  

[Recording Link](https://youtu.be/wj5fm_YvhEk)

[Slides](https://docs.google.com/presentation/d/1XGxuK-oB7ZuOFZ_UJB7sYAe3_Ltyb7IM5iXHFv4X7bY/edit?usp=sharing)

[Lecture Notes](https://hackmd.io/@gubsheep/B1LF02t9i)

[Exercises](https://hackmd.io/@gubsheep/Hy57lluOs)

  

‣

**Session 2 (Wednesday 1/11) Circom 1** (Brian Gu)

This session focuses on practical zkSNARK circuit engineering: using a toolstack (circom/snarkjs/zkREPL) for the groth16 zkSNARK protocol to build simple zero-knowledge proofs. We’ll discuss the R1CS programming model (and cost model), and simple circuit components such as bit operators, range checks, and more.

  

[Recording Link](https://youtu.be/El64GK_rM6c)

[Slides](https://docs.google.com/presentation/d/1-dqNpq5kmfJphz13uw0yNgSd-esPwq9r919gwYLPp8I/edit?usp=sharing)

[Lecture Notes](https://hackmd.io/@gubsheep/Hyx1hho5o)

[Exercises](https://hackmd.io/@gubsheep/S1Hz96Yqo)

  

‣

**Session 3 (Friday 1/13) Mathematical building blocks** (Yufei Zhao)

In this session, we’ll discuss some of the basic “building blocks” of modern proof systems, including: formalization of zero-knowledge, discrete logarithm and other common cryptographic sources of “hardness,” elliptic curve cryptography, and pairing-based cryptography.

[Recording Link](https://www.youtube.com/watch?v=Ja-xlDR-_7Y)

  

[Lecture notes - math building blocks.pdf3210.7KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/b42768d1-4e53-40be-8208-671508dd3cc8.pdf)

  

[Exercises - math building blocks (updated Jan 14)122.4KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/ae255934-f5c2-437e-bda8-9d1c03e7379e.pdf)

  

‣

**Session 4 (Tuesday 1/17) Circom 2** (Vivek Bhupatiraju)

_Note that this session will take place on Tuesday, as Monday is MLK day._

Building off “Circom 1,” we’ll write and discuss more complex circuits: inclusion proof verification, hash functions, signature and encryption verification.

  

  

[snarkjs resources](https://zkiap.com/snarkjs)

[Recording Link](https://www.youtube.com/watch?v=CjaMn9bMeFg)

[Slides](https://docs.google.com/presentation/d/1zNVGTdDrxpE-wFmWYncOBV-Vv87YN_uVHvWQQ3yoeuo/edit?usp=sharing)

[Lecture Notes](https://hackmd.io/@vb7401/zk-crypto-4)

Exercises: Check out [https://semaphore.appliedzkp.org/](https://semaphore.appliedzkp.org/) and set up a starter project!

  

‣

**Session 5 (Wednesday 1/18) Commitment Schemes** (Ying Tong Lai)

We’ll build off of the “mathematical building blocks” session to construct vector, univariate polynomial, and multivariate polynomial commitment schemes.

[Recording Link](https://youtu.be/2aL3mP6AI3c)

  

[Lecture Notes - Commitment Schemes.pdf315.0KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/61fb28e6-f2dc-420f-89e1-cc8000233a4f.pdf)

  

[Exercises - Commitment Schemes.pdf103.3KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/6b91c8d4-bda1-4354-9504-849079e7bb69.pdf)

  

[Solutions 5 - Commitment Schemes.pdf173.7KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/7d9e02af-940f-489c-aaad-018a9252758d.pdf)

  

‣

**Session 6 (Friday 1/20) Algorithms for Efficient Cryptographic Operations** (Jason Morton)

We’ll discuss techniques for efficient openings and polynomial arithmetic, including number-theoretic transform (NTT); multi-scalar multiplication (MSM); fast elliptic curve double-and-add operations.

[Recording Link](https://youtu.be/bTiNNw8lHpc)

Lecture Notes

  

[6th session notes.pdf57599.4KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/9c584d49-d3c3-4d25-ab07-1cf44c378852.pdf)

  

‣

**Session 7 (Monday 1/23) Arithmetizations** (Ying Tong Lai)

We discuss a few examples of arithmetizations—intermediate representations of ZK programs and circuits which can be consumed by a proving system.

[Recording Link](https://www.youtube.com/watch?v=PRyNIUjksoY)

  

[Lecture Notes - Arithmetisations.pdf389.3KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/e11309fb-7356-42ad-9c78-565341abd80d.pdf)

  

‣

**Session 8 (Wednesday 1/25) PLONK and polynomial identities.** (Jason Morton)

We dive into the PLONK zkSNARK protocol—a zkSNARK construction based on polynomial commitment schemes, and a particular PLONK-style arithmetization. We also discuss arguments like LOOKUP, built from polynomial identities.

[Recording Link](https://youtu.be/ABI7Jmhvxuw)

Lecture Notes

  

[8th Session notes.pdf57184.7KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/837c9d9c-58e2-4986-9790-962370cf7a8b.pdf)

  

‣

**Session 9 (Friday 1/27) Proving systems stack; recursion and composition.** (Ying Tong Lai)

Based on the learnings from previous four sessions, we’ll give an overview of the zkSNARK protocol landscape, and build up a taxonomy of proving systems. We’ll also discuss proof system recursion and composition.

[Recording Link](https://youtu.be/SDOmw2TL20g)

  

[Lecture 9 - Proof Systems Stack.pdf438.2KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/a17715ac-e666-48ec-867c-3bb3087a107d.pdf)

  

[Lecture 9 - Recursion & Proof Composition.pdf7964.1KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/b3ec5337-0876-463b-a61c-efb1e72d4f08.pdf)

  

  

‣

**Session 10 (Monday 1/30) Applied ZK Constructions 1** (Aayush Gupta)

We’ll discuss ZK constructions in the wild: membership proofs for pseudonymous messaging, nullifier-based constructions for private digital currency transfers, zk-email, and more.

[Recording Link](https://youtu.be/2lGFj0Exfb8)

[Slides](https://docs.google.com/presentation/d/1lou0dhoekxTaMKRekpXlSMcALs_SH_JcEWHoXoOKlas/edit#slide=id.g2018a704be6_12_96)

  

‣

**Session 11 (Wednesday 2/1) Applied ZK Constructions 2** (Brian Gu)

We’ll discuss additional uses of zkSNARKs: incomplete information games, encrypted data marketplaces, ZKML, ZKVMs, recursive ZK proofs, and more.

[Recording Link](https://youtu.be/7zjkrsod6go)

[Slides 1](https://docs.google.com/presentation/d/1x9WZWQDMZuR2Z8uO6M79SHHBAqK0PGyeXbNS7TuwpY0/edit?usp=sharing)

  

[dark forest - zkiap.key43063.1KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/47dc46e1-c37b-46b2-8694-a04048e851aa.key)

  

‣

**Session 12 (Friday 2/3) Student and Staff Demos**

In our final session, students and staff will demonstrate projects and ZK applications that they’ve been working on over IAP!

[Recording Link](https://www.youtube.com/playlist?list=PLNK7oFq6eaEwU--JTfGJo9waoXI-t-UgP)

# Student Notes

  

[fareed\_sheriff\_notes\_updated\_jan\_31\_2023.pdf561.4KB](https://assets.super.so/9c1ce0ba-bad4-4680-8c65-3a46532bf44a/files/4349aae7-ea0d-46c9-bdeb-68d58cf57fe5.pdf)

*   This excellent set of notes by ZKIAP participant Fareed Sheriff goes through a lot of the prerequisite material found at [learn.0xparc.org](http://learn.0xparc.org/)
*   Currently goes up to Lecture 9 - Proof Systems

  

# Course Staff

This course is designed and taught by a team of researchers and developers, with experience across the applied zero-knowledge cryptography “stack.”

**Ying Tong Lai** is a researcher at Geometry and 0xPARC. Previously, she was a senior engineer at [Electric Coin Company](https://electriccoin.co/), and a core developer of the [Halo2 zkSNARK protocol and library](https://zcash.github.io/halo2/).

**Yufei Zhao** is an Associate Professor of Mathematics at MIT.

**Brian Gu** is co-founder of [0xPARC Foundation](https://0xparc.org/), an R&D organization developing [open-source infrastructure](https://github.com/0xPARC) for [applications](https://www.technologyreview.com/2022/11/10/1062981/dark-forest-blockchain-video-game-creates-metaverse/) of zero-knowledge cryptography.

**Jason Morton** is an Associate Professor of Mathematics at Penn State and the CEO of ZKonduit, where he is building [tools for zero-knowledge machine learning inference](https://github.com/zkonduit/ezkl).

**Aayush Gupta** is a research steward at [Personae Labs](http://personaelabs.org/), a research group focused on building zero-knowledge primitives for digital identity and more.

**Vivek Bhupatiraju** is a research steward at [Personae Labs](http://personaelabs.org/), a research group focused on building zero-knowledge primitives for digital identity and more.

  

# Prerequisites

You should have familiarity with:

*   Elementary number theory and group theory. You should be comfortable working through the material in [this handout](https://mit6875.github.io/HANDOUTS/numbertheory.pdf) from MIT’s 6.875 (Foundations of Cryptography) course.
*   Basic cryptographic primitives. You should be comfortable with the idea of hash functions, encryption and signature schemes, and cryptographic accumulators (i.e. Merkle Trees); ideally, you’ve had some experience using and manipulating these primitives in practical settings (for example, perhaps you’ve implemented or used a signature verification API in an application).
*   Basic algebraic concepts. You should be comfortable with basic manipulation of polynomials, perhaps with a bit of reading: polynomial multiplication and division, [Lagrange interpolation](https://en.wikipedia.org/wiki/Lagrange_polynomial), [probabilistic polynomial identity testing](https://en.wikipedia.org/wiki/Schwartz%E2%80%93Zippel_lemma), fast Fourier transform, and working in [field extensions](https://en.wikipedia.org/wiki/Field_extension).

Some engineering or software development experience will also be beneficial, as we’ll be discussing the practical use of modern cryptographic primitives for real applications.

  

# Logistics

This program will take place during MIT’s Independent Activities Period (1/9 - 2/3). This is a not-for-credit program. Communication will take place on a class Discord server. We expect the time commitment for this program to range from 10 to 20 hours per week, depending on whether you opt to join the optional project component, and whether you opt to complete the optional and ungraded problem sets.

  

**Lectures and workshops**

*   **When:** Mondays, Wednesdays, and Fridays, from 2:00 - 3:30PM (with the exception of 1/16, which is MLK day—that session will instead take place on 1/17).
*   **Where:** Classroom 4-237

Anyone is welcome to attend any lectures, regardless of whether or you are working on a project, or whether you’ve attended previous lectures. Lectures will be recorded and made publicly available.

  

**Office hours**

*   **When**: Tuesdays 10AM - 12PM and Thursdays 5PM - 7PM.
*   **Where**: 2-136

On Tuesdays and Thursdays, we’ll run smaller office hours / co-working sessions, for students interested in building a ZK project, receiving guidance on the optional problem sets, or learning about supplementary topics.

  

# Class components

## Recommended P**roject**

**We highly encourage interested to participate in the optional project component, to solidify their understanding of the material.** Course staff will provide mentorship for students interested in building a ZK project over the course of the month. Projects may include:

*   A full-stack application of ZK crypto, such as an anonymous voting app, a p2p/decentralized game, a cryptocurrency mixer, etc.
*   A library of useful ZK primitives, such as ZK circuits for a ZK-friendly encryption scheme.
*   An implementation of a zero-knowledge proof system or some key component parts, along with a series of tutorials or writeups.
*   Documentation or educational material, such as a series of blog posts or tutorials explaining a ZK proof system.

Projects from teams that have participated in past 0xPARC educational programs have included:

*   [**zkREPL**](https://zkrepl.dev/), an in-browser collaborative development environment for writing ZK circuits.
*   [**circom-ecdsa**](https://0xparc.org/blog/zk-ecdsa-1), an implementation of Ethereum’s signature algorithms in zkSNARK circuits.
*   [**zkmessage.xyz**](https://0xparc.org/blog/zk-group-sigs), a demonstration of how zkSNARKs can be used to emulate and extend other cryptographic primitives, such as ring signatures.
*   [**Zordle**](https://zordle.xyz/), a webapp that allows you to generate zero-knowledge proofs that [your Wordle guess diagram is legitimate](https://twitter.com/evan_van_ness/status/1596389622132920322). A subproject of Zordle involved [porting the Halo2 ZK proving system to WASM](https://zcash.github.io/halo2/user/wasm-port.html).

Certain Tuesday and Thursday office hour sessions will be set aside for project brainstorming, team-matching, and mentorship and co-working sessions.

Interested students should submit a project proposal during the second week of the program. A final demos session will be scheduled in the last week of the program.

## Optional Exercises and Problem Sets

Most lectures will be accompanied by problems sets or sets of “conceptual exercises.” These sets may include math problems; understanding questions which ask you to sketch out a protocol at a high level; coding tasks; and more. **Problem sets are ungraded, though we highly recommend that you complete them for your own understanding**; you’re also welcome to come in on Tuesdays and Thursdays to ask course staff to review your solutions, or to check your understanding.