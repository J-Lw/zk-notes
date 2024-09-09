### ZK Intro

- Zero-knowledge proofs are a technique that enables an entity (the prover) to communicate to another entity (the verifier) that a given statement is true without havng to reveal any information other than the fact the statement is true.
- Sound zk proof algorithms possess three main properties: completeness, soundness, zero-knowledge.
- In basic settings, meaningfull zk proofs require a degree of interaction between the prover and verifier.
- The interaction between p & v typically involves the v asking the p a series of random questions.
- The random nature of the questions asked and the correct responses from p, convinces the v of p's knowledge.
- Without the interaction, a v could potentially share the proof with a third party, falsely portraying their possession of the hidden knowledge.
- Specific models allow for non-interactive zkp.
