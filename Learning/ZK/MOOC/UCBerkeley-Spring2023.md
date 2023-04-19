## Introduction and History of ZKP 
| [Lecture](https://www.youtube.com/watch?v=uchjTIlPzFo) | [Quiz](https://forms.gle/Td2Kw3Btp9XBHw846) | [Slides](https://zk-learning.org/assets/Lecture1-2023-slides.pdf)

  

**Readings**

*   [\[Goldwasser-Micali-Rackoff’89\] Knowledge Complexity of Interactive Proof Systems](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Proof%20Systems/The_Knowledge_Complexity_Of_Interactive_Proof_Systems.pdf)
*   [\[Goldreich-Micali-Wigderson’86\] How to prove all NP-statements in zero-knowledge, and a methodology of cryptographic protocol design](https://link.springer.com/chapter/10.1007/3-540-47721-7_11)
*   [\[Fiat-Shamir’86\] How To Prove Yourself: Practical Solutions to Identification and Signature Problems](https://link.springer.com/chapter/10.1007/3-540-47721-7_12)
*   [\[Bellare-Goldreich’92\] On Defining Proofs of Knowledge](https://www.wisdom.weizmann.ac.il/~oded/PSX/pok.pdf)

  

**Other Helpful Resources**

*   [Introduction to Zero Knowledge - Alon Rosen](https://www.youtube.com/watch?v=6uGimDYZPMw)
*   [Proofs of Knowledge - Yehuda lindell](https://www.youtube.com/watch?v=RvGsjnoYRRg)
*   [Demonstration of Zero-Knowledge Proof for Sudoku Using Standard Playing Cards](https://www.wisdom.weizmann.ac.il/~naor/PAPERS/SUDOKU_DEMO/)
*   [Boaz Barak - Zero Knowledge](https://files.boazbarak.org/crypto/lec_14_zero_knowledge.pdf)

  

## Overview of Modern SNARK Constructions 
| [Lecture](https://youtu.be/bGEXYpt3sj0) | [Playlist](https://youtube.com/playlist?list=PLS01nW3Rtgoo_0Y-X5bQ32SyDbMiGFqee) | [Quiz](https://forms.gle/94fRTqREjKnacyP3A) | [Slides](https://zk-learning.org/assets/Lecture2-2023.pdf)

  

**Readings**

*   [Schwartz-Zippel Lemma - Section 1](https://www.cs.ubc.ca/~nickhar/W12/Lecture9Notes.pdf)
*   [Anca Nitulescu - zk-SNARKs: A Gentle Introduction](https://www.di.ens.fr/~nitulesc/files/Survey-SNARKs.pdf)
*   [Using ZK Proofs to Fight Disinformation](https://medium.com/@boneh/using-zk-proofs-to-fight-disinformation-17e7d57fe52f)
*   [Zero Knowledge Canon](https://a16zcrypto.com/zero-knowledge-canon)

  

Libraries and Compilers to build ZKP | [Lecture](https://youtu.be/UpRSaG6iuks) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgoqqvF39f11ncNAClgSLPlXD) | [Quiz](https://forms.gle/WZZuArS4jmJuaAJR6) | [Slides](https://zk-learning.org/assets/lecture3-2023.pdf)

  

**Resources**

*   [Code from Lecture](https://github.com/rdi-berkeley/zkp-course-lecture3-code)
*   [Circom Documentation](https://docs.circom.io/)
*   [Arkworks Tutorial](https://github.com/arkworks-rs/r1cs-tutorial/)
*   [ZoKrates Documentation](https://zokrates.github.io/)

  

## Interactive Proofs (IP) 
| [Lecture](https://youtu.be/4018OYyoAf8) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgopePvLcZgMJK8gC5trUWVsT) | [Quiz](https://forms.gle/KghozdFAvXuenHdp6) | [Slides](https://zk-learning.org/assets/lecture4.pdf)

  

**Readings**

*   [Interactive Proofs and the Sum-Check Protocol](https://theory.cs.princeton.edu/complexity/book.pdf)
*   [Chapters 3 and 4 of \[Thaler\]](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
*   [Merkle Trees](https://en.wikipedia.org/wiki/Merkle_tree)
*   [Sum-Check-Based Polynomial IOPs for Circuit-SAT](https://eprint.iacr.org/2014/846.pdf)

**Other Helpful Resources**

*   [Spartan](https://eprint.iacr.org/2019/550)
*   [Hyrax](https://eprint.iacr.org/2017/1132)
*   [vSQL](https://faculty.cc.gatech.edu/~genkin/papers/vsql.pdf)
*   [Libra](https://eprint.iacr.org/2019/317.pdf)

  

## Plonk Interactive Oracle Proofs (IOP) 
| [Lecture](https://youtu.be/A0oZVEXav24) | [Playlist](https://youtube.com/playlist?list=PLS01nW3Rtgopdkrlu2-Lqgg7MKIS2vv2J) | [Quiz](https://forms.gle/j3VZ6iARCoCb16Qp6) | [Slides](https://zk-learning.org/assets/lecture5-2023.pdf)

  

**Readings**

*   [Constant-Size Commitments to Polynomials and Their Applications](https://www.iacr.org/archive/asiacrypt2010/6477178/6477178.pdf)
*   [Feist-Khovratovich technique for computing KZG proofs fast](https://alinush.github.io/2021/06/17/Feist-Khovratovich-technique-for-computing-KZG-proofs-fast.html)
*   [Dory: Efficient, Transparent arguments for Generalised Inner Products and Polynomial Commitments](https://eprint.iacr.org/2020/1274)
*   [PLONK: Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge](https://eprint.iacr.org/2019/953)
*   [HyperPlonk: Plonk with Linear-Time Prover and High-Degree Custom Gates](https://eprint.iacr.org/2022/1355)
*   [PLONKish Arithmetization](https://zcash.github.io/halo2/concepts/arithmetization.html)

  

## Discrete-log-based Polynomial Commitments 
| [Lecture](https://youtu.be/WyT5KkKBJUw) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgopRnH84Omx0C4yZo75uSHWO) | [Quiz](https://forms.gle/gyKY676K3DMc7kiFA) | [Slides](https://zk-learning.org/assets/lecture6.pdf)

  

**Readings**

*   [A Zero-Knowledge Version of vSQL](https://eprint.iacr.org/2017/1146)
*   [Bulletproofs: Short Proofs for Confidential Transactions and More](https://eprint.iacr.org/2017/1066.pdf)

  

## ZKP based on Error-Correcting Codes 
| [Lecture](https://youtu.be/1S7ZjqG9uyI) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgopEpcPnXiXsHPO8HsaGUgmd) | [Quiz](https://forms.gle/7L1gk7VP6a9BYcaC8) | [Slides](https://zk-learning.org/assets/lecture7.pdf)

  

**Readings**

*   [Ligero: Lightweight Sublinear Arguments Without a Trusted Setup](https://acmccs.github.io/papers/p2087-amesA.pdf)
*   [Orion: Zero Knowledge Proof with Linear Prover Time](https://eprint.iacr.org/2022/1010)
*   [Brakedown: Linear-time and post-quantum SNARKs for R1CS](https://eprint.iacr.org/2021/1043)

  

## Transparent ZKP 
| [Lecture](https://youtu.be/A3edAQDPnDY) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgorRZsBnqch6gGBStZB9VVrM) | [Quiz](https://forms.gle/nG6aQCGbMTgsn9wz7) | [Slides](https://zk-learning.org/assets/lecture8.pdf)

  

**Readings**

*   [FRI Paper](https://eccc.weizmann.ac.il/report/2017/134/)
*   [Best Existing Soundness Analysis of FRI](https://eprint.iacr.org/2020/654.pdf)
*   [Polynomial Commitments from FRI](https://eprint.iacr.org/2019/1020)
*   [Round-by-round Soundness, Fiat-Shamir, and Sum-check](https://eprint.iacr.org/2018/1004.pdf)

  

## Linear Probabilistically Checkable Proofs (PCP) 
| [Lecture](https://youtu.be/I7TXIHXamwM) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgorEgSixlZA2rJ-2q7_eAKe3) | [Quiz](https://forms.gle/nK8DtvAwcBuXGLeW7) | [Slides](https://zk-learning.org/assets/lecture9.pdf)

  

**Readings**

*   [Pinocchio](https://eprint.iacr.org/2013/279.pdf)
*   [Succinct Non-Interactive Arguments via Linear Interactive Proofs](https://eprint.iacr.org/2012/718)
*   [Groth16](https://eprint.iacr.org/2016/260.pdf)

  

## Recursive SNARKs, Aggregation and Accumulation 
| [Lecture](https://youtu.be/0LW-qeVe6QI) | [Playlist](https://youtube.com/playlist?list=PLS01nW3RtgopkbOmAfolTngGbnJ3SYmYu) | [Quiz](https://forms.gle/3mM7HLtQNruGU2Pv6) | [Slides](https://zk-learning.org/assets/lecture10.pdf)

  

**Readings**

*   [Recursive STARK Proofs](https://medium.com/starkware/recursive-starks-78f8dd401025)
*   [Incrementally Verifiable Computation via Incremental PCPs](https://eprint.iacr.org/2019/1407)
*   [Scalable Zero Knowledge via Cycles of Elliptic Curves](https://eprint.iacr.org/2014/595.pdf)
*   [Nova](https://eprint.iacr.org/2021/370.pdf)
*   [Proof-Carrying Data without Succinct Arguments](https://eprint.iacr.org/2020/1618.pdf)
*   [Folding Schemes with Selective Verification](https://eprint.iacr.org/2022/1576.pdf)