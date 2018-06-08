# Block-Chain-
I will implement a node that’s part of a block-chain-based distributed consensus protocol. The BlockChain class is responsible for maintaining a block chain. Since the entire block chain could be huge in size, we should only keep around the most recent blocks. The exact number to store is up to our design, as long as we are able to implement all the API functions.    Since there can be (multiple) forks, blocks form a tree rather than a list. Our design should take this into account. We have to maintain a UTXO pool corresponding to every block on top of which a new block might be created.   
