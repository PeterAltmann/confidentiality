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

# Other techniques list

[Old work slide](https://docs.google.com/presentation/d/1ioo4R7EjExQtZC8XvajdokEdoRXy3uckFNA6WY1sbbk/edit?usp=sharing)

* One time / stealth addresses (sender vs reciever generated), e.g., BIP32HD
* Sign an unknown message using blind signatures
* Hide the signer in a group, e.g., ring signatures
* [Commitment schemes](https://en.wikipedia.org/wiki/Commitment_scheme), e.g., Pedersen commitments
* Mixers and tumblers
* Blinding identifiers e.g., (onlookers know that SUM_INPUTS == SUM_OUTPUTS, but cannot tell amounts, transacting parties can tell amount)
* Private channel based techniques e.g., Fabric, Quorum
* Merged list checks e.g., Google's Private Join ()
* Combinations of the above (e.g., [Private Join and Compute](https://venturebeat.com/2019/06/19/googles-private-join-and-compute-gives-companies-data-insights-while-preserving-privacy/) with this [github repo](https://github.com/Google/private-join-and-compute))
