## II. The Mempool and MEV


## Ethereum's Mempool (The Dark Forest)

**"Whenever you make a transaction in the Ethereum network (you sign the transaction), you have to wait until it to be confirmed in the blockchain. During that period, it sits in the memory pool. Anyone can listen to these transactions, and their details, while they are there, and even modify them. If someone pays a higher gas price, their modification will be included a block first."**

---

## MEVs

*"Miner extractable value (MEV) is a measure devised to study consensus security by modeling the profit a miner (or validator, sequencer, or other privileged protocol actor) can make through their ability to arbitrarily include, exclude, or re-order transactions from the blocks they produce. MEV includes both ‘conventional’ profits from transaction fees and block rewards, and ‘unconventional’ profits from transaction reordering, transaction insertion, and transaction censorship within the block a miner is producing."* - Alex Obadia

* MEV exists in places where there is high complexity which requires significant knowledge of smart contracts to understand. 
* ~90% arbritage 

## Arbritage bots

* Monitor pending transactions and attempt to exploit profitabe opportunities.
* Usually loo for specific types of transactions in the mempool, such as DEX trade or an oracle update


--

## References

* [Frontrunning MEV crisis](https://writings.flashbots.net/writings/frontrunning-mev-crisis/)