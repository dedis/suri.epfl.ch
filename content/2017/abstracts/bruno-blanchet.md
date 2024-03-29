TLS 1.3 is the next version of the Transport Layer Security (TLS) protocol. Its clean-slate design is a reaction both to the increasing demand for low-latency HTTPS connections, and to a series of recent high-profile attacks on TLS.  The hope is that a fresh protocol with modern cryptography will prevent legacy problems; the danger is that it will expose new kinds of attacks, or reintroduce old flaws that were fixed in previous versions of TLS.  After 18 drafts, the protocol is nearing completion, and the working group has appealed to researchers to analyze the protocol before publication.

We respond by presenting a comprehensive analysis of TLS 1.3 Draft-18:

(1) We present symbolic ProVerif models for various intermediate versions of TLS 1.3 and evaluate them against a rich class of attacks to reconstruct both known and previously unpublished vulnerabilities that influenced the current design of the protocol. In particular, we test whether TLS 1.3 prevents well-known attacks on TLS 1.2, such as Logjam or the Triple Handshake, even if it is run in parallel with TLS 1.2.

(2) We present a computational CryptoVerif model for TLS 1.3 Draft-18 and mechanically prove its security under standard (strong) assumptions on its cryptographic primitives.

(3) We present RefTLS, an interoperable implementation of TLS 1.0-1.3 and automatically analyze its protocol core by extracting a ProVerif model from its typed JavaScript code.

The talk will mainly focus on (2) and briefly sketch (1) and (3).
