## Minimum viable blockchain
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">A Primer</span></span>

---

## <span style="font-family:Rockitt; font-weight:bold">Origin </span>
<span style="font-family:Hattori Hanzo;"> The Blockchain is a concept introduced by the anonymous Satoshi Nakamoto in his groundbreaking Bitcoin paper. </span>

---

## <span style="font-family:Rockitt; font-weight:bold"> What the Blockchain promises</span>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Decentralization</span> 
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">Immutability</span> 
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;">Validation</span> 
<br>
<span class="fragment" data-fragment-index="4" style="font-family:Hattori Hanzo;">Incentive</span>  

---

## <span style="font-family:Rockitt; font-weight:bold">What the Blockchain is</span>

<span style="font-family:Hattori Hanzo;">An ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without changing proof-of-work. </span>

--- 

## <span style="font-family:Rockitt; font-weight:bold">How a Blockchain works</span>

<br>

+++ 

<span style="font-family:Rockitt; font-weight:bold">
Who plays Banker in Monopoly?
</span>
<br>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;"> Alice has 100 Units. This goes in a block at the top of the chain.</span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;"> Alice pays Bob 50 Units, this goes into a new block, and the block is linked to the previous. This is a ledger of sorts. </span>
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;"> How do you keep these records without a central third party?</span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Why double spend when you can triple spend?
</span>
<br>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;"> What stops Alice from paying Charlie 75 Units now. </span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;"> Bob and Charlie race to validate to see if this is a valid transaction. If it is, the fastest add it to the chain. </span>
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;"> But whats to stop anyone say Bob, from passing a false validation?</span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Elizabeth creates 6 nodes in her name and starts churning out false transactions 
</span>
<br>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;"> 51 % problem</span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;"> Validation/Entry cost: Computational power and time would act as a powerful deterrent. </span>
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;"> But why would anyone want to validate expending power? </span> 

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
