# awesome-post-quantum [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources about post-quantum cryptography.

To contribute, please file a PR. Please list items alphabetically.

## Initiatives

* [NIST's Post-Quantum Cryptography
  Project](https://csrc.nist.gov/projects/post-quantum-cryptography/post-quantum-cryptography-standardization) ([Selected Algorithms 2022](https://csrc.nist.gov/projects/post-quantum-cryptography/selected-algorithms-2022) announcement)
* [Open Quantum Safe](https://openquantumsafe.org/)
* [US Department of Homeland Security roadmap](https://www.dhs.gov/quantum)


## Learning Resources

* [IACR ePrint](https://www.google.com/search?q=site%3Aeprint.iacr.org+%22post-quantum%22)
* [NSA Post-Quantum Cryptography FAQ](https://media.defense.gov/2021/Aug/04/2002821837/-1/-1/1/Quantum_FAQs_20210804.PDF)
* [pqcrypto.org](https://pqcrypto.org/) (incl. conference series)

SoK-type papers:

* [A Decade of Lattice-Based Cryptography](https://eprint.iacr.org/2015/939.pdf) by Chris Peikert
* [Mathematics of Isogeny-Based Cryptography](https://arxiv.org/abs/1711.04062) by Luca de Feo


## Applications

* [Microsoft/PQCrypto-VPN](https://github.com/Microsoft/PQCrypto-VPN)
* [StarkWare](https://starkware.co/) (PQ proofs of knowledge)


## Libraries

* [aws/s2n-tls](https://github.com/aws/s2n-tls/tree/main/pq-crypto)
* [kudelskisecurity/crystals-go](https://github.com/kudelskisecurity/crystals-go)
* [Microsoft/PQCrypto-LWEKE](https://github.com/Microsoft/PQCrypto-LWEKE) (FrodoKEM)
* [Microsoft/PQCrypto-SIDH](https://github.com/Microsoft/PQCrypto-SIDH)
* [mupq/pqm4](https://github.com/mupq/pqm4)
* [open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs)
* [PQClean/PQClean](https://github.com/PQClean/PQClean)
* [rustpq/pqcrypto](https://github.com/rustpq/pqcrypto)
* [wultra/sike-java](https://github.com/wultra/sike-java)


## Algorithms 

## NIST Round 3

Code-based:

* [BIKE](https://www.esat.kuleuven.be/cosic/pqcrypto/saber/) (KEM, alternate candidate, **round 4**)
* [Classic McEliece](https://classic.mceliece.org/) (KEM, finalist, **round 4**)
* [HQC](https://www.pqc-hqc.org/) (KEM, alternate candidate, **round 4**)

Hash-based:

* [SPHINCS+](https://sphincs.org/) (signature, alternate candidate, **selected**)

Isogeny-based:

* [SIKE](https://sike.org/) (KEM, alternate candidate, **round 4**)

Lattice-based:

* [Dilithium](https://pq-crystals.org/dilithium/) (signature, finalist, **selected**)
* [Falcon](https://falcon-sign.info/) (signature, finalist, **selected**)
* [FrodoKEM](http://frodokem.org/) (KEM, alternate candidate)
* [Kyber](https://pq-crystals.org/kyber) (KEM, finalist, **selected**)
* [NTRU](https://ntru.org/) (KEM, finalist)
* [NTRU Prime](https://ntruprime.cr.yp.to/) (KEM, alternate candidate)
* [SABER](https://www.esat.kuleuven.be/cosic/pqcrypto/saber/) (KEM, finalist)

MQ-based:

* [GeMSS](https://www-polsys.lip6.fr/Links/NIST/GeMSS.html) (signature,
  alternate candidate)
* [Rainbow](https://www.pqcrainbow.org/) (signature, finalist)

ZKP-based:

* [Picnic](https://microsoft.github.io/Picnic/) (signature, alternate
  candidate)


## Other Algorithms

* All [NIST Round 1 submissions](https://csrc.nist.gov/Projects/post-quantum-cryptography/Round-1-Submissions)

Isogeny-based:

* [CSIDH](https://csidh.isogeny.org/) (KEM)


## Companies

Respectable companies offering PQ solutions:

* [AWS](https://docs.aws.amazon.com/kms/latest/developerguide/pqtls.html)
* [IBM](https://www.zurich.ibm.com/securityprivacy/quantumsafecryptography.html)
* [PQShield](https://pqshield.com/)


## Standardization Efforts

IETF:

* ID [Framework to Integrate Post-quantum Key Exchanges into Internet Key Exchange Protocol Version 2 (IKEv2)](https://datatracker.ietf.org/doc/html/draft-tjhai-ipsecme-hybrid-qske-ikev2-04)
* ID [Hybrid Post-Quantum Key Encapsulation Methods (PQ KEM) for Transport Layer Security 1.2 (TLS)](https://datatracker.ietf.org/doc/html/draft-campagna-tls-bike-sike-hybrid)
* ID [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)
* RFC 8391: [XMSS: eXtended Merkle Signature Scheme](https://datatracker.ietf.org/doc/html/rfc8391)
* RFC 8554: [Leighton-Micali Hash-Based Signatures](https://datatracker.ietf.org/doc/html/rfc8554)


## Misc

* [PQC WIKI](https://pqc-wiki.fau.edu/w/Special:DatabaseHome)
* [SUPERCOP](https://bench.cr.yp.to/results-kem.html) (benchmarks)
* [You could have broken SIDH](https://yx7.cc/blah/2022-08-22.html)
