A lisiting of terminology for internal consistent use at the DCI, but published to serve as reference externally. PR's welcome!

Ideally, we will tag a release once this is somewhat populated. We should probably standardize capitalization.

The tricky part is that upper-case bitcoin might mean something different than lower-case, but suggest that we use uppercase for everything on this list and note anything that should be in lower case. - Joi

# Dictionary

| Term | Definition |
| --- | --- |
| Bitcoin | |
| bitcoin | |
| Blind Signature | A digital signature where the content of a message is disguised before it is signed. This allows privacy to be maintained when the message author and signer are different parties. |
| Blockchain Technology | Blockchain technology may refer to any form of public ledger that solves the double-spending and consensus problems or can mean more narrowly a public ledger based on the Bitcoin proof of work system. |
| Blockchain, The | "The Blockchain" is the Bitcoin ledger connected to the Bitcoin genesis block. |
| Bloom Filter| A probablistic set data structure, the "opposite" of a cache. Can return a false positive for membership, but never a false negative. |
| Byzantine Fault Tolerance | A system that can continue to operate with up to _f_ failures under the byzantine failure model. Under this failure model, faulty nodes may operate arbitrarily.|
| Censorship Resistant | A system is censorship resistant if no user can block another user's actions |
| Consensus ||
| Consistency | Every node in the network is guaranteed to have some amount of information be the same |
| Core Developer | A developer with commit access to the main source code repository for a project. |
| Core Contributor | A developer who has written code that has been accepted into the main source code repository for a project. |
| Core Maintainer | The lead Core Developer for a project, oversees development, merges, and releases.|
| Fork ||
| Hard Fork ||
| Hash | |
| Hash Chain | The successive application of a hash function to a piece of data. The hash function can be applied successively to additional pieces of data in order to record the chronology of data's existence and secure non-repudiation. |
| Hash Rate | |
| Jeremy Rubin | Bitcoin hacker and generally viewed as a troublemaker. |
| Ledger ||
| Merkle Tree | a hash tree data structure for efficiently committing to information. Informally, given a hash h, MerkleTree(h,a) = h(MerkleTree(a[:half])+MerkleTree(a[half:])). Proofs of membership are O(log n)|
| Mining ||
| Node ||
| Non-repudiation | A state where the validity of a signature will not be able to be successfully challenged. |
| Private Key ||
| Proof of Stake | |
| Proof of Work (pow) ||
| Public Key | |
| Public Key Infrastructure (PKI) ||
| Scalability ||
| SHA-256 | A strong one-way encryption algorithm which generates a 64 character long unique string for any given input. |
| Sidechain ||
| Signature | |
| Soft Fork ||
| Tidbit | |
| Timestamp | |
| Transaction| Generally, an operation that should have at most once semantics, such as a transfer of funds. |
| User ||
| Validating ||
| Wallet | The software used for interfacing with a cryptocurrency to create new transactions or view previous activity. |
| Zero Knowledge Proof | A proof which does not reveal the way in which is was proved. For example, it could be proven that one knows the prime factors of a number without revealing the factors. |

_We may want to put these in a different document but:_

## Other Bitcoin glossaries and dictionaries

| Site | URL |
| --- | --- |
| Bitcoin Simplified | http://bitcoinsimplified.org/definitions/ |
| Bitcoin.org | https://bitcoin.org/en/vocabulary |
| coinbase | https://support.coinbase.com/customer/portal/articles/1833695-bitcoin-glossary |
| CoinDesk | http://www.coindesk.com/information/bitcoin-glossary/ |
| Oleg Andreev | https://github.com/oleganza/bitcoin-papers/blob/master/BitcoinGlossary.md |

