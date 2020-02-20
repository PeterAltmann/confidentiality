# Zero knowledge proofs

[Link to awesome list](https://github.com/matter-labs/awesome-zero-knowledge-proofs)

In essence: Prove that you know something, without revealing anything about how you know.

Elevator explanation:

1. Completeness: a test to fully convince someone that you know what you claim you know
2. Soundness: a test should only be able to convince of a truth but not a lie
3. Zero-knowledge: reveal nothing else to the person but the fact that you know

Example use: Prove that A and B are different (1) without revealing anything about A or B (3) in a public setting (2).

# Homomorphic encryption

[Link to awesome list](https://github.com/jonaschn/awesome-he)

In essence: Perform computation on ciphertexts

Elevator explanation:

1. Rely you cryptography to secure privacy / confidentiality as opposed to access control (cf [links](https://www.techrepublic.com/article/is-homomorphic-encryption-ready-to-deliver-confidential-cloud-computing-to-enterprises/))
2. Includes a wide set of different types of encryption schemes that can perform different classes of computation on data
3. Paremtrization is key (i.e., understanding what you want to keep secret and what you want to optimize for).

# Differential privacy

[Link to awesome list](https://github.com/menisadi/awesome-differential-privacy)

In essence: Allows turning data into insights without revealing anything *specific* about a participating actor (we can still learn things about an actor)

Elevator explanation:

1. Privacy guarantees during both computation and in output.
2. Attempts to address the composition problem (not knowing what already has been revealed or will be revealed) e.g., by adding random noise or randomized response techniques
3. Allows us to quantify privacy loss accumulatively on analyses performed on an actor's data.
4. Privacy achived by allowing a small error in the resulting output (accuracy tradeoff)

# Privacy preserving Machine Learning

* Applies various techniques from above
* [Awesome list here](https://github.com/mortendahl/awesome-ppml)
