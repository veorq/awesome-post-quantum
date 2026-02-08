# awesome-post-quantum [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources about post-quantum cryptography.

To contribute, please file a PR. Please list items alphabetically.

If you notice errors or obsolete content, please file PR or an Issue.


## Government initiatives and recommendations

### United States

* [NIST's PQC Project](https://csrc.nist.gov/projects/post-quantum-cryptography/post-quantum-cryptography-standardization) ([Selected Algorithms 2022](https://csrc.nist.gov/projects/post-quantum-cryptography/selected-algorithms-2022) announcement)
* [DHS PQC approach and roadmap](https://www.dhs.gov/quantum)
* [NSA PQC FAQ](https://media.defense.gov/2021/Aug/04/2002821837/-1/-1/1/Quantum_FAQs_20210804.PDF)
* [NIST and NCCoE's Migration to PQC](https://www.nccoe.nist.gov/sites/default/files/2022-07/pqc-migration-project-description-final.pdf)

### Europe

**European Union:**

* [ENISA Post-Quantum Cryptography Reports](https://www.enisa.europa.eu/topics/cryptography)
* [ETSI Quantum-Safe Cryptography Specification Group](https://www.etsi.org/committee/1430-qsc)

**Czech Republic:**

* [Minimum Requirements for Cryptographic Algorithms](https://nukib.gov.cz/download/publications_en/Minimum%20Requirements%20for%20Cryptographic%20Algorithms.pdf)
* [Quantum Threat and Quantum Resistant Cryptography](https://nukib.gov.cz/download/publications_en/Annex%20to%20the%20document_Minimum%20Requirements%20for%20Cryptographic%20Algorithms.pdf)


**France:**

* [ANSSI's views](https://cyber.gouv.fr/en/publications/follow-position-paper-post-quantum-cryptography)

**Germany:**

* [BSI Cryptographic Mechanisms Recommendations (TR-02102-1)](https://www.bsi.bund.de/EN/Topics/CryptographicAlgorithms/cryptographic-algorithms_node.html)
* [BSI Post-Quantum Cryptography Recommendations](https://www.bsi.bund.de/EN/Topics/Companies-and-Organisations/Information-and-Recommendations/Quantum-safe-cryptography/quantum-safe-cryptography_node.html)

**Netherlands:**

* [AIVD/MIVD Quantum Threat Assessments](https://english.aivd.nl/)

**United Kingdom:**

* [NCSC's Next steps in preparing for post-quantum cryptography](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography)

### Asia-Pacific

**Australia:**

* [Australian Cyber Security Centre (ACSC) Quantum Security Resources](https://www.cyber.gov.au/acsc)
* [Australian Signals Directorate (ASD) Quantum Computing Guidance](https://www.cyber.gov.au/)

**China:**

* TBD

**Japan:**

* [CRYPTREC PQC Evaluation](https://www.cryptrec.go.jp/en/)

**Singapore:**

* [CSA Post-Quantum Cryptography Guidelines](https://www.csa.gov.sg/)

**South Korea:**

* [KpqC Competition](https://kpqc.or.kr/competition_02.html)

### Other regions

**Canada:**

* [Communications Security Establishment (CSE) Quantum Threat Assessments](https://www.cse-cst.gc.ca/)

**International:**

* [GSMA: Post Quantum Government Initiatives by Country and Region](https://www.gsma.com/newsroom/post-quantum-government-initiatives-by-country-and-region)
* [ISO/IEC JTC 1/SC 27 Working Group on PQC Standardization](https://www.iso.org/committee/45306.html)


## Hyperscalers and major tech companies

**Apple:**

* [iMessage with PQ3 protocol](https://security.apple.com/blog/imessage-pq3/) - Post-quantum cryptographic protocol for iMessage
* [Security research blog on PQC](https://security.apple.com/)

**AWS:**

* [AWS PQC Initiative](https://aws.amazon.com/security/post-quantum-cryptography/)
* [AWS KMS post-quantum TLS](https://aws.amazon.com/blogs/security/post-quantum-tls-now-supported-in-aws-kms/)
* [s2n-tls PQC implementation](https://github.com/aws/s2n-tls/tree/main/pq-crypto)

**Cloudflare:**

* [Post-quantum cryptography blog series](https://blog.cloudflare.com/tag/post-quantum/)
* [The post-quantum future](https://blog.cloudflare.com/post-quantum-future/)
* [Sizing up post-quantum signatures](https://blog.cloudflare.com/sizing-up-post-quantum-signatures/)
* [CIRCL: Cloudflare Interoperable Reusable Cryptographic Library](https://github.com/cloudflare/circl)

**Google:**

* [Post-quantum cryptography in Chrome](https://security.googleblog.com/2024/08/post-quantum-cryptography-standards.html)
* [Quantum computing threat timeline](https://security.googleblog.com/2023/08/toward-quantum-resilient-security-keys.html)
* [FIDO2/WebAuthn post-quantum security keys](https://security.googleblog.com/)
* [BoringSSL post-quantum experiments](https://github.com/google/boringssl)

**IBM:**

* [IBM Quantum Safe](https://www.ibm.com/quantum/quantum-safe)
* [Quantum Safe Roadmap](https://www.ibm.com/quantum/quantum-safe/roadmap)
* [Cryptographic Bill of Materials (CBOM)](https://www.ibm.com/quantum/quantum-safe/cbom)

**Microsoft:**

* [Microsoft PQC program](https://www.microsoft.com/en-us/research/project/post-quantum-cryptography/)
* [Azure Quantum Cryptography](https://azure.microsoft.com/en-us/products/quantum/)
* [Reference implementations](https://github.com/Microsoft/PQCrypto-LWEKE)

**Signal:**

* [PQXDH: Post-Quantum Extended Diffie-Hellman](https://signal.org/docs/specifications/pqxdh/)
* [Signal's approach to post-quantum encryption](https://signal.org/blog/pqxdh/)


## Research resources

* [IACR ePrint](https://www.google.com/search?q=site%3Aeprint.iacr.org+%22post-quantum%22)
* [pqcrypto.org](https://pqcrypto.org/) (incl. conference series)
* [PQC Forum](https://groups.google.com/a/list.nist.gov/g/pqc-forum) - NIST's discussion list
* [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/) - relevant for understanding threat models

### Survey papers

* [A Decade of Lattice-Based Cryptography](https://eprint.iacr.org/2015/939.pdf) by Chris Peikert
* [A Survey on Code-Based Cryptography](https://arxiv.org/abs/2201.07119) by Violetta Weger, Niklas Gassner and Joachim Rosenthal
* [Mathematics of Isogeny-Based Cryptography](https://arxiv.org/abs/1711.04062) by Luca de Feo
* [Post-Quantum Cryptography](https://www.researchgate.net/profile/Nicolas-Sendrier-2/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) by Daniel J. Bernstein, Johannes Buchmann and Erik Dahmen
* [Post-quantum cryptography—dealing with the fallout of physics success](https://eprint.iacr.org/2017/314) by Daniel J. Bernstein and Tanja Lange
* [The Learning with Errors Problem](https://cims.nyu.edu/~regev/papers/lwesurvey.pdf) by Oded Regev

### Technical articles and blog posts

**Cloudflare:**

* [The state of the post-quantum Internet](https://blog.cloudflare.com/post-quantum-internet/)
* [Experimenting with post-quantum cryptography](https://blog.cloudflare.com/post-quantum-key-encapsulation/)
* [Sizing up post-quantum signatures](https://blog.cloudflare.com/sizing-up-post-quantum-signatures/)
* [Towards post-quantum cryptography in TLS](https://blog.cloudflare.com/towards-post-quantum-cryptography-in-tls/)

**Trail of Bits:**

* [Quantifying post-quantum readiness](https://blog.trailofbits.com/2024/01/25/quantifying-post-quantum-readiness/)
* [The treachery of post-quantum signatures](https://blog.trailofbits.com/2023/03/01/the-treachery-of-post-quantum-signatures/)

**Google:**

* [Protecting Chrome traffic with hybrid kyber KEM](https://security.googleblog.com/2023/08/protecting-chrome-traffic-with-hybrid.html)
* [Experimenting with post-quantum cryptography](https://security.googleblog.com/2016/07/experimenting-with-post-quantum.html)


## NIST post-quantum cryptography standardization

* Homepage [NIST Post-Quantum Cryptography](https://csrc.nist.gov/Projects/post-quantum-cryptography)
* All [Round 1 submissions](https://csrc.nist.gov/Projects/post-quantum-cryptography/Round-1-Submissions)

### Algorithms selected for standardization

#### Selected in 2022

Lattice-based:

* [Kyber](https://pq-crystals.org/kyber) (KEM)
    - [FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard](https://csrc.nist.gov/pubs/fips/203/final)
* [Dilithium](https://pq-crystals.org/dilithium/) (signature)
    - [FIPS 204: Module-Lattice-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/204/final)
* [Falcon](https://falcon-sign.info/) (signature)

Hash-based:

* [SPHINCS+](https://sphincs.org/) (signature)
    - [FIPS 205: Stateless Hash-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/205/final)

#### Selected in 2025

Code-based:

* [HQC](https://www.pqc-hqc.org/) (KEM)

### Historical context: earlier round submissions

#### Round 3 submissions

(Only listing those that were not selected for standardization or round 4)

Lattice-based:

* [FrodoKEM](http://frodokem.org/) (KEM, alternate candidate)
* [NTRU](https://ntru.org/) (KEM, finalist)
* [NTRU Prime](https://ntruprime.cr.yp.to/) (KEM, alternate candidate)
* [SABER](https://www.esat.kuleuven.be/cosic/pqcrypto/saber/) (KEM, finalist)

MQ-based:

* [GeMSS](https://www-polsys.lip6.fr/Links/NIST/GeMSS.html) (signature, alternate candidate)
* [Rainbow](https://www.pqcrainbow.org/) (signature, finalist)

ZKP-based:

* [Picnic](https://microsoft.github.io/Picnic/) (signature, alternate candidate)

#### Round 4 submissions

(Only listing those that were not selected for standardization)

Code-based:

* [BIKE](https://bikesuite.org/) (KEM)
* [Classic McEliece](https://classic.mceliece.org/) (KEM)

Isogeny-based:

* [SIKE](https://sike.org/) (KEM)
    - **Withdrawn in 2022** after catastrophic cryptanalytic breakthrough. See [You could have broken SIDH](https://yx7.cc/blah/2022-08-22.html). This demonstrates the continued risks in algorithm maturity assessment even at advanced standardization stages.


## NIST PQC additional digital signature schemes

This project, launched after the selection of 4 signature schemes in 2022, aims to select algorithms "that are not based on structured lattices" and/or "that have short signatures and fast verification."

* Homepage [PQC Digital Signature Schemes](https://csrc.nist.gov/projects/pqc-dig-sig)
* [Round 1 submissions](https://csrc.nist.gov/Projects/pqc-dig-sig/round-1-additional-signatures)
* [Round 2 submissions](https://csrc.nist.gov/Projects/pqc-dig-sig/round-2-additional-signatures)
* [Comparison tool](https://pqshield.github.io/nist-sigs-zoo/)


## Other national standards

### China

* [GB/T 38635-2020](https://www.chinesestandard.net/PDF/English.aspx/GBT38635-2020) - Information security technology—Digital signature algorithm based on SM9 identification cryptographic algorithm

### South Korea

[KpqC Competition](https://kpqc.or.kr/competition_02.html) selected algorithms:

* [AIMer](https://www.kpqc.or.kr/images/pdf/AIMer.pdf) (signature)
* [HAETAE](https://kpqc.cryptolab.co.kr/haetae) (signature)
* [NTRU+](https://www.kpqc.or.kr/images/pdf/NTRU+.pdf) (KEM)
* [SMAUG-T](https://kpqc.cryptolab.co.kr/smaug-t) (KEM)


## Software projects

This list includes notable implementations on a best-effort basis. Inclusion does not imply endorsement. 

### General purpose libraries

* [Open Quantum Safe](https://openquantumsafe.org/)
* [open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs)
* [PQClean/PQClean](https://github.com/PQClean/PQClean)
* [PQ Code Package](https://github.com/pq-code-package) (a Linux Foundation [PQCA](https://pqca.org/) project building high-assurance implementations of standards-track algorithms)
* [Bouncy Castle](https://www.bouncycastle.org/) - Java/C# crypto library with PQC support
* [Google Tink](https://github.com/google/tink) - Multi-language crypto library with PQC support

### Language-specific implementations

**Go:**

* [Go crypto/ml-kem](https://pkg.go.dev/golang.org/x/crypto/mlkem) - Official Go implementation of Kyber/ML-KEM

**JavaScript/TypeScript:**

* [paulmillr/noble-post-quantum](https://github.com/paulmillr/noble-post-quantum) - Dilithium, Kyber, SPHINCS+ in JavaScript

**Rust:**

* [RustCrypto/KEMs](https://github.com/RustCrypto/KEMs) - ML-KEM (Kyber) and Classic McEliece
* [RustCrypto/signatures](https://github.com/RustCrypto/signatures) - ML-DSA (Dilithium), Falcon, SPHINCS+
* [rustpq/pqcrypto](https://github.com/rustpq/pqcrypto)

### Protocol implementations

* [aws/s2n-tls](https://github.com/aws/s2n-tls/tree/main/pq-crypto)
* [wolfSSL](https://www.wolfssl.com/post-quantum-cryptography/)
* [OpenSSL PQC Provider](https://github.com/openssl/openssl) (via OQS)
* [Post-Quantum TLS](https://www.pq-tls.org/)

### Embedded/constrained devices

* [mupq/pqm4](https://github.com/mupq/pqm4)

### Algorithm-specific reference implementations

Official, authors' implementations of the NIST-selected algorithms:

* [Kyber](https://pq-crystals.org/kyber/software.shtml)
* [Dilithium](https://pq-crystals.org/dilithium/software.shtml)
* [Falcon](https://falcon-sign.info/impl/falcon.h.html)
* [SPHINCS+](https://sphincs.org/software.html)
* [HQC](https://pqc-hqc.org/implementation.html)

### Deprecated/historical implementations

* [Microsoft/PQCrypto-LWEKE](https://github.com/Microsoft/PQCrypto-LWEKE) (FrodoKEM)
* [Microsoft/PQCrypto-SIDH](https://github.com/Microsoft/PQCrypto-SIDH) - **Note: SIDH/SIKE was broken in 2022. Use for historical reference only.**


## IETF specifications

Internet Drafts and RFCs:

* ID [Framework to Integrate Post-quantum Key Exchanges into Internet Key Exchange Protocol Version 2 (IKEv2)](https://datatracker.ietf.org/doc/html/draft-tjhai-ipsecme-hybrid-qske-ikev2-04)
* ID [Hybrid Post-Quantum Key Encapsulation Methods (PQ KEM) for Transport Layer Security 1.2 (TLS)](https://datatracker.ietf.org/doc/html/draft-campagna-tls-bike-sike-hybrid)
* ID [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)
* RFC 8391: [XMSS: eXtended Merkle Signature Scheme](https://datatracker.ietf.org/doc/html/rfc8391)
* RFC 8554: [Leighton-Micali Hash-Based Signatures](https://datatracker.ietf.org/doc/html/rfc8554)


## Other algorithms

Algorithms that are neither NIST-standardized nor NIST competition
submissions (unexhaustive list):

Hash-based:

* [PRUNE-HORST](https://github.com/gravity-postquantum/prune-horst) (few-times signature)
* [SPHINCS+C](https://github.com/sphincs/sphincsplus) (signature, compact variant of SPHINCS+)

Isogeny-based:

* [CSIDH](https://csidh.isogeny.org/) (KEM)
* [SQIsign](https://sqisign.org/) (signature)

MQ-based (Multivariate Quadratic):

* [Rainbow](https://www.pqcrainbow.org/) (signature, **broken** - included for historical reference)


## Practical implementation resources

### Benchmarking & performance

* [SUPERCOP](https://bench.cr.yp.to/results-kem.html) - Benchmarks for cryptographic software
* [PQShield NIST Signatures Zoo](https://pqshield.github.io/nist-sigs-zoo/) - Interactive comparison tool
* [PQC Performance Tracker](https://openquantumsafe.org/benchmarking/)

### Deployment & migration guidance

* [PQCrypto Usage & Deployment](https://ianix.com/pqcrypto/pqcrypto-deployment.html)
* [PQC Cheat Sheet](https://github.com/marioschiener/PQC-Cheat-Sheet)
* [NIST Migration to Post-Quantum Cryptography](https://www.nccoe.nist.gov/crypto-agility-considerations-migrating-post-quantum-cryptographic-algorithms)
* Quantum Doomsday Planning blog posts:
    - [1/2: Risk assessment & quantum attacks](https://www.taurushq.com/blog/quantum-doomsday-planning-2-2-the-post-quantum-technology-landscape/)
    - [2/2: The post-quantum technology landscape](https://www.taurushq.com/blog/quantum-doomsday-planning-2-2-the-post-quantum-technology-landscape/)

### Educational resources

* [PQCHacks: a gentle introduction to post-quantum cryptography (slides)](https://cr.yp.to/talks/2015.12.27/slides-dan+tanja-20151227-16x9.pdf)
* ["Fancy" Cryptography](https://github.com/fancy-cryptography/fancy-cryptography)
* [Introduction to post-quantum cryptography](https://www.youtube.com/watch?v=wGHRg96KJN0) by Daniel J. Bernstein
* [NIST PQC Standardization: Process and Lessons Learned](https://csrc.nist.gov/Presentations/2023/nist-post-quantum-cryptography-standardization)


## Related resources

* [awesome-quantum-computing](https://github.com/desireevl/awesome-quantum-computing)
* [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software)
* [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography)

