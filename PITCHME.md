## Minimum viable blockchain
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">A Primer</span></span>

---

## <span style="font-family:Rockitt; font-weight:bold">Origin </span>
<span style="font-family:Hattori Hanzo;"> The Blockchain is a concept introduced by the anonymous Satoshi Nakamoto in his groundbreaking Bitcoin paper. </span>

---

## <span style="font-family:Rockitt; font-weight:bold"> What the Blockchain tries to provide </span>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Decentralization </span> 
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">Immutability</span> 
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;">Validation</span> 
<span class="fragment" data-fragment-index="4" style="font-family:Hattori Hanzo;">Incentive</span>  

---

## What the Blockchain is

An ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without changing proof-of-work

--- 

## How a Blockchain should work

<br>

+++ 

Who plays Banker in Monopoly?

+++

- Alice has 100 Units. This goes in a block at the top of the chain. 
- Alice pays Bob 50 Units, this goes into a new block, and the block is linked to the previous. This is a ledger of sorts. 
- How do you keep these records without a central third party? 

+++

Why double spend when you can triple spend?

+++

- What stops Alice from paying Charlie 75 Units now. 
- Bob and Charlie race to validate to see if this is a valid transaction. If it is, the fastest add it to the chain. 
- But whats to stop anyone say Bob, from passing a false validation?  

+++

Elizabeth creates 6 nodes in her name and starts churning out false transactions 

+++
 - 51 % problem 
 - Validation/Entry cost: Computational power and time would act as a powerful deterrent  
 - But why would anyone want to validate expending power?  

---

## Minimum viable features for a basic blockchain

<br>

The bare minimum any blockchain should have

+++

Public Key Infrastructure
- Every user needs a private-public key pair. |
- Private key signing is used to Authenticate origin/Peer. |

+++

Consensus 
- Why 2/3PC or Paxos wont work | 
- What do you drop in CAP? |

+++

Proof of Work  
- Guard against Sybill Attacks |
- Make voting expensive | 
- Hashcash |

+++

Immutability 
- Merkle Trees | 

---

## Exciting non financial uses for blockchains

+++

 - Voting
 - Supply Chain
 - Ride Sharing
 - Notary Services and government documentation

---
