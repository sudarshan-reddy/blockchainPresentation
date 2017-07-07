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

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">
--> Alice has 100 Units. This goes in a block at the top of the chain
<br>
--> Alice pays Bob 50 Units, this goes into a new block, and the block is linked to the previous. This is a ledger of sorts.
<br>
--> How do you keep these records without a central third party?
</span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Why double spend when you can triple spend?
</span>
<br>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">
--> What stops Alice from paying Charlie 75 Units now.
<br>
--> Bob and Charlie race to validate to see if this is a valid transaction. If it is, the fastest add it to the chain.
<br>
--> But whats to stop anyone say Bob, from passing a false validation?
</span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Elizabeth creates 6 nodes in her name and starts churning out false transactions 
</span>
<br>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">
--> 51 % problem
<br>
--> Validation/Entry cost: Computational power and time would act as a powerful deterrent.
<br>
--> But why would anyone want to validate expending power? 
</span> 

---

## <span style="font-family:Rockitt; font-weight:bold"> Minimum viable features for a basic blockchain </span>

<br>

<span style="font-family:Hattori Hanzo;"> The bare minimum any blockchain should have </span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Public Key Infrastructure
</span> 
<br>
<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Every user needs a private-public key pair.</span> 
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">Private key signing is used to Authenticate origin/Peer. </span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Consensus 
</span>
<br>
<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Why 2/3PC or Paxos wont work </span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">What do you drop in CAP? </span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Proof of Work  
</span>
<br>
<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Guard against Sybill Attacks </span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">Make validation expensive </span>
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;">Hashcash </span>

+++

<span style="font-family:Rockitt; font-weight:bold">
Immutability 
</span>

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Merkle Trees </span>

---

<span style="font-family:Rockitt; font-weight:bold">
## Possible non financial uses for blockchains
</span>  

<span class="fragment" data-fragment-index="1" style="font-family:Hattori Hanzo;">Voting</span>
<br>
<span class="fragment" data-fragment-index="2" style="font-family:Hattori Hanzo;">Supply Chain</span>
<br>
<span class="fragment" data-fragment-index="3" style="font-family:Hattori Hanzo;">Ride Sharing</span>
<br>
<span class="fragment" data-fragment-index="4" style="font-family:Hattori Hanzo;">Notary Services and government documentation</span>

---

<span style="font-family:Rockitt; font-weight:bold">
## Thank you
</span>
