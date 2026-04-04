# awesome-post-quantum [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources about post-quantum cryptography.

To contribute, please file a PR. Please list items alphabetically.

If you notice errors or obsolete content, please file PR or an Issue.


## U.S. standards and guidelines 

Standardization projects: 
*  [NIST Post-Quantum Cryptography](https://csrc.nist.gov/Projects/post-quantum-cryptography)
* [PQC Digital Signature Schemes](https://csrc.nist.gov/projects/pqc-dig-sig) (in progress)

### NIST standard algorithms

KEMs (encryption, key agreement):

* [Kyber](https://pq-crystals.org/kyber) - Selected in 2022
    - [FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard (ML-KEM)](https://csrc.nist.gov/pubs/fips/203/final)
    -  [Kyber official software](https://pq-crystals.org/kyber/software.shtml)
* [HQC](https://www.pqc-hqc.org/) - Selected in 2025
  - [HQC official software](https://pqc-hqc.org/implementation.html)

Signature schemes:

* [Dilithium](https://pq-crystals.org/dilithium/) - Selected in 2022
    - [FIPS 204: Module-Lattice-Based Digital Signature Standard (ML-DSA)](https://csrc.nist.gov/pubs/fips/204/final)
    - [Dilithium official software](https://pq-crystals.org/dilithium/software.shtml)
* [Falcon](https://falcon-sign.info/) - Selected in 2022
  - [Falcon official software](https://falcon-sign.info/impl/falcon.h.html)
* [SPHINCS+](https://sphincs.org/) - Selected in 2022
    - [FIPS 205: Stateless Hash-Based Digital Signature Standard (SLH-DSA)](https://csrc.nist.gov/pubs/fips/205/final)
  -  [SPHINCS+ official software](https://sphincs.org/software.html)

### Migration guidelines

* [DHS PQC approach and roadmap](https://www.dhs.gov/quantum)
* [NSA PQC FAQ](https://media.defense.gov/2021/Aug/04/2002821837/-1/-1/1/Quantum_FAQs_20210804.PDF)
* [NIST and NCCoE's Migration to PQC](https://www.nccoe.nist.gov/sites/default/files/2022-07/pqc-migration-project-description-final.pdf)
* [NIST Migration to Post-Quantum Cryptography](https://www.nccoe.nist.gov/crypto-agility-considerations-migrating-post-quantum-cryptographic-algorithms)


## Other national initiatives

* [GSMA: Post Quantum Government Initiatives by Country and Region](https://www.gsma.com/newsroom/post-quantum-government-initiatives-by-country-and-region)
* [ISO/IEC JTC 1/SC 27 Working Group on PQC Standardization](https://www.iso.org/committee/45306.html)
* [Quantum Computing Cybersecurity Preparedness Act](https://www.congress.gov/bill/117th-congress/house-bill/7535/text)

Australia:

* [Australian Signals Directorate (ASD): Planning for post-quantum cryptography
](https://www.cyber.gov.au/business-government/secure-design/quantum/planning-for-post-quantum-cryptography)


Canada:

* [Communications Security Establishment (CSE) Quantum Threat Assessments](https://www.cse-cst.gc.ca/)

China:

* [Next-Generation Commercial Cryptographic Algorithms Program (NGCC)](https://www.niccs.org.cn/en/)

Czech Republic:

* [Minimum Requirements for Cryptographic Algorithms](https://nukib.gov.cz/download/publications_en/Minimum%20Requirements%20for%20Cryptographic%20Algorithms.pdf)
* [Quantum Threat and Quantum Resistant Cryptography](https://nukib.gov.cz/download/publications_en/Annex%20to%20the%20document_Minimum%20Requirements%20for%20Cryptographic%20Algorithms.pdf)

EU: 

* [ENISA Post-Quantum Cryptography Reports](https://www.enisa.europa.eu/topics/cryptography)
* [ETSI Quantum-Safe Cryptography Specification Group](https://www.etsi.org/committee/1430-qsc)

India:

* [Implementation of Quantum Safe Ecosystem in India](https://dst.gov.in/sites/default/files/Report_TaskForce_PQMigration_4Feb26%20%28v1%29.pdf)

Japan:

* [CRYPTREC PQC Evaluation](https://www.cryptrec.go.jp/en/)

France:

* [ANSSI's views](https://cyber.gouv.fr/en/publications/follow-position-paper-post-quantum-cryptography)

Germany:

* [BSI Cryptographic Mechanisms Recommendations (TR-02102-1)](https://www.bsi.bund.de/EN/Topics/CryptographicAlgorithms/cryptographic-algorithms_node.html)
* [BSI Post-Quantum Cryptography Recommendations](https://www.bsi.bund.de/EN/Topics/Companies-and-Organisations/Information-and-Recommendations/Quantum-safe-cryptography/quantum-safe-cryptography_node.html)

Netherlands:

* [AIVD's PQC Migration Handbook](https://english.aivd.nl/documents/2024/12/3/the-pqc-migration-handbook)

Singapore:

* [CSA Post-Quantum Cryptography Guidelines](https://www.csa.gov.sg/)

South Korea:

* [KpqC Competitions and Algorithms](https://kpqc.or.kr/)
* Standardized algorithms:
  * [NTRU+](https://www.kpqc.or.kr/images/pdf/NTRU+.pdf) - KEM
  * [SMAUG-T](https://kpqc.cryptolab.co.kr/smaug-t) - KEM
  * [AIMer](https://www.kpqc.or.kr/images/pdf/AIMer.pdf) - Signature
  * [HAETAE](https://kpqc.cryptolab.co.kr/haetae) - Signature

United Kingdom:

* [NCSC's Next steps in preparing for post-quantum cryptography](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography)


## IETF standards and proposals

RFCs:

* RFC 8391: [XMSS: eXtended Merkle Signature Scheme](https://datatracker.ietf.org/doc/html/rfc8391)
* RFC 8554: [Leighton-Micali Hash-Based Signatures](https://datatracker.ietf.org/doc/html/rfc8554)
* RFC 8784: [Mixing Preshared Keys in the Internet Key Exchange Protocol Version 2 (IKEv2) for Post-quantum Security](https://datatracker.ietf.org/doc/html/rfc8784)
* RFC 9881: [Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Module-Lattice-Based Digital Signature Algorithm (ML-DSA)](https://datatracker.ietf.org/doc/html/rfc9881)
* RFC 9935: [Internet X.509 Public Key Infrastructure - Algorithm Identifiers for the Module-Lattice-Based Key-Encapsulation Mechanism (ML-KEM) ](https://datatracker.ietf.org/doc/rfc9935/)
* RFC 9794: [Terminology for Post-Quantum Traditional Hybrid Schemes ](https://www.rfc-editor.org/rfc/rfc9794.html)


Internet-Drafts:

* ID [Framework to Integrate Post-quantum Key Exchanges into Internet Key Exchange Protocol Version 2 (IKEv2)](https://datatracker.ietf.org/doc/html/draft-tjhai-ipsecme-hybrid-qske-ikev2-04)
* ID [Hybrid Post-Quantum Key Encapsulation Methods (PQ KEM) for Transport Layer Security 1.2 (TLS)](https://datatracker.ietf.org/doc/html/draft-campagna-tls-bike-sike-hybrid)
* ID [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)
* ID [Composite ML-DSA for use in X.509 Public Key Infrastructure](https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-sigs/)
* ID [Merkle Tree Certificates](https://datatracker.ietf.org/doc/draft-ietf-plants-merkle-tree-certs/)
* ID [Post-quantum hybrid ECDHE-MLKEM Key Agreement for TLSv1.3](https://datatracker.ietf.org/doc/draft-ietf-tls-ecdhe-mlkem/)
* ID [Use of ML-DSA in TLS 1.3](https://datatracker.ietf.org/doc/draft-ietf-tls-mldsa/)
* ID [Use of Composite ML-DSA in TLS 1.3](https://datatracker.ietf.org/doc/draft-reddy-tls-composite-mldsa/)
* ID [ML-KEM Post-Quantum Key Agreement for TLS 1.3 ](https://datatracker.ietf.org/doc/draft-ietf-tls-mlkem/)
* ID [Post-Quantum and Post-Quantum/Traditional Hybrid Algorithms for HPKE](https://datatracker.ietf.org/doc/draft-ietf-hpke-pq/)
* ID [Downgrade Prevention for the Internet Key Exchange Protocol Version 2 (IKEv2) ](https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-downgrade-prevention/)
* ID [Post-quantum Key Exchange with ML-KEM in the Internet Key Exchange Protocol Version 2 (IKEv2) ](https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-mlkem/)



## From tech companies

Apple:

* [iMessage with PQ3 protocol](https://security.apple.com/blog/imessage-pq3/)
* [Security research blog on PQC](https://security.apple.com/)

AWS:

* [AWS PQC Initiative](https://aws.amazon.com/security/post-quantum-cryptography/)
* [AWS KMS post-quantum TLS](https://aws.amazon.com/blogs/security/post-quantum-tls-now-supported-in-aws-kms/)
* [s2n-tls PQC implementation](https://github.com/aws/s2n-tls/tree/main/pq-crypto)

Cloudflare:

* [PQC solutions overview](https://www.cloudflare.com/pqc/)
* [State of the post-quantum Internet in 2025](https://blog.cloudflare.com/pq-2025/)
* [A look at the latest post-quantum signature standardization candidates](https://blog.cloudflare.com/another-look-at-pq-signatures/)
* [You don’t need quantum hardware for post-quantum security](https://blog.cloudflare.com/you-dont-need-quantum-hardware/)
* [Keeping the Internet fast and secure: introducing Merkle Tree Certificates](https://blog.cloudflare.com/bootstrap-mtc/)

Google:

* [Building superconducting and neutral atom quantum computers](https://blog.google/innovation-and-ai/technology/research/neutral-atom-quantum-computers/)
* [Quantum frontiers may be closer than they appear](https://blog.google/innovation-and-ai/technology/safety-security/cryptography-migration-timeline/)
* [Post-quantum cryptography in Chrome](https://security.googleblog.com/2024/08/post-quantum-cryptography-standards.html)
* [FIDO2/WebAuthn post-quantum security keys](https://security.googleblog.com/)

IBM:

* [IBM Quantum Safe](https://www.ibm.com/quantum/quantum-safe)
* [Quantum Safe Roadmap](https://www.ibm.com/quantum/quantum-safe/roadmap)
* [Cryptographic Bill of Materials (CBOM)](https://www.ibm.com/quantum/quantum-safe/cbom)

Meta:


* [Post-quantum readiness for TLS at Meta](https://engineering.fb.com/2024/05/22/security/post-quantum-readiness-tls-pqr-meta/)

Microsoft:

* [Microsoft PQC program](https://www.microsoft.com/en-us/research/project/post-quantum-cryptography/)
* [Azure Quantum Cryptography](https://azure.microsoft.com/en-us/products/quantum/)
* [LWEKE Reference implementations](https://github.com/Microsoft/PQCrypto-LWEKE)
* [Post-Quantum TLS](https://www.microsoft.com/en-us/research/project/post-quantum-tls/)

Signal:

* [PQXDH: Post-Quantum Extended Diffie-Hellman](https://signal.org/docs/specifications/pqxdh/)
* [Signal's approach to post-quantum encryption](https://signal.org/blog/pqxdh/)

Tencent:

* [PQC InfoHub](https://pqc.tencent.com/en)

Trail of Bits:

* [Quantifying post-quantum readiness](https://blog.trailofbits.com/2024/01/25/quantifying-post-quantum-readiness/)
* [The treachery of post-quantum signatures](https://blog.trailofbits.com/2023/03/01/the-treachery-of-post-quantum-signatures/)




## PQC software

* [SUPERCOP](https://bench.cr.yp.to/results-kem.html) - Benchmarks for cryptographic software

### General-purpose libraries with PQC support

Des not include TLS implementations listed later:

* [AWS-LC](https://github.com/aws/aws-lc/blob/main/crypto/fipsmodule/PQREADME.md) - Rust bindings in [aws-lc-rs](https://github.com/aws/aws-lc-rs)
* [Bouncy Castle](https://www.bouncycastle.org/) - Java/C# 
* [CIRCL (Cloudflare Interoperable, Reusable Cryptographic Library)](https://github.com/cloudflare/circl) - Go
* [Google Tink](https://github.com/tink-crypto) - Multi-language (C++, Go, Java, Obj-C, Python) 



### PQC libraries and language-specific software

C:

* [liboqs](https://github.com/open-quantum-safe/liboqs) - From [Open Quantum Safe](https://openquantumsafe.org/)
* [PQ Code Package](https://github.com/pq-code-package) - A Linux Foundation [PQCA](https://pqca.org/) project building high-assurance implementations of standards-track algorithms (
* [mupq/pqm4](https://github.com/mupq/pqm4) - PQC library for the ARM Cortex-M4
* [algorand/falcon](https://github.com/algorand/falcon) - Deterministic FALCON implementation

Go:

* [Go crypto/mlkem](https://pkg.go.dev/crypto/mlkem) - Official Go implementation of Kyber/ML-KEM

JavaScript:

* [paulmillr/noble-post-quantum](https://github.com/paulmillr/noble-post-quantum) - ML-KEM, ML-DSA, SLH-DSA, Falcon, and hybrids 


.NET:

* [Post-Quantum Cryptography in .NET](https://devblogs.microsoft.com/dotnet/post-quantum-cryptography-in-dotnet/)

Rust:

* [RustCrypto/KEMs](https://github.com/RustCrypto/KEMs) - ML-KEM, FrodoKem
* [RustCrypto/signatures](https://github.com/RustCrypto/signatures) - ML-DSA, SLH-DSA, LMS
* [libcrux](https://crates.io/crates/libcrux) - Formally verified code

Zig:

* [std.crypto](https://www.mintlify.com/ziglang/zig/api/crypto) -
  ML-DSA and ML-KEM in the standard library




### TLS implementations with PQC support

* [aws/s2n-tls](https://github.com/aws/s2n-tls/)
* [BoringSSL](https://boringssl.googlesource.com/boringssl)
* [OpenSSL](https://www.openssl.org/)
* [Go crypto/tls](https://github.com/golang/go/tree/master/src/crypto/tls)
* [wolfSSL](https://github.com/wolfSSL/wolfssl)

## Research surveys

* [A Decade of Lattice-Based Cryptography](https://eprint.iacr.org/2015/939.pdf) by Chris Peikert
* [A Survey on Code-Based Cryptography](https://arxiv.org/abs/2201.07119) by Violetta Weger, Niklas Gassner and Joachim Rosenthal
* [Mathematics of Isogeny-Based Cryptography](https://arxiv.org/abs/1711.04062) by Luca de Feo
* [Post-Quantum Cryptography](https://www.researchgate.net/profile/Nicolas-Sendrier-2/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) by Daniel J. Bernstein, Johannes Buchmann and Erik Dahmen
* [Post-quantum cryptography—dealing with the fallout of physics success](https://eprint.iacr.org/2017/314) by Daniel J. Bernstein and Tanja Lange
* [The Learning with Errors Problem](https://cims.nyu.edu/~regev/papers/lwesurvey.pdf) by Oded Regev


## Other resources

* [PQC Forum](https://groups.google.com/a/list.nist.gov/g/pqc-forum) - NIST's discussion list
* [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org)
* [PQCrypto Usage & Deployment](https://ianix.com/pqcrypto/pqcrypto-deployment.html)
* [awesome-quantum-computing](https://github.com/desireevl/awesome-quantum-computing)
* [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software)











