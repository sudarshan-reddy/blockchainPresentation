## Minimum viable blockchain
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">A Primer</span></span>

---

## Origin
The Blockchain is a concept introduced by the anonymous Satoshi Nakamoto in his groundbreaking Bitcoin paper.

---

## Salient features

<br>

What the Blockchain tries to provide

+++

- Decentralization |
- Immutability     |
- Validitation     |
- Incentive        | 

---

## What the Blockchain is

An ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without changing proof-of-work

--- 

## How a Blockchain should work

<br>

+++ 

Who plays Banker in Monopoly?

+++

- Alice, Bob, Charlie and Diana are four peers in a network. |
- Alice has 100 Units. This goes in a block at the top of the chain. |
- Alice pays Bob 50 Units, this goes into a new block, and the block is linked to the previous. This is a ledger of sorts. |
- How do you keep these records without a central third party? |

+++

Why double spend when you can triple spend?

+++

- Alice tries to pay Charlie 75 Units now. |
- How does everyone know Alice doesn't have the money? | 
- Bob and Charlie race to validate to see if this is a valid transaction. If it is, the fastest add it to the chain. |
- But whats to stop anyone say Bob, from passing a false validation? | 
- The other nodes will know the transaction that was published and will instantly reject this. |
- This is called Quorum consensus. Whatever the majority of the nodes deem valid is valid. |

+++

Elizabeth creates 6 nodes in her name and starts churning out false transactions 

+++
 - The downside of quorum consensus : 51 % problem |
 - What if every validation/entry comes with a cost? | 
 - Computational power and time would act as a powerful deterrent | 
 - But why would anyone want to validate expending power? | 
 - Pay them |

---

## Minimum viable features for a basic blockchain

<br>

The bare minimum any blockchain should have

+++

Public Key Infrastructure

+++

Public Key Infrastructure
- Every user needs a private-public key pair. |
- Private key signing is used to Authenticate origin/Peer. |

+++

Consensus 

+++

Consensus 
- Why 2/3PC or Paxos wont work | 
- What do you drop in CAP? |

+++

Proof of Work 

+++

Proof of Work  |
- Guard against Sybil Attacks |
- Make voting expensive | 
- Hashcash |

+++

Immutability 

+++

- Merkle Trees | 

---

## Exciting non financial uses for blockchains

+++

 - Voting
 - Supply Chain
 - Ride Sharing
 - Notary Services and government documentation

---
