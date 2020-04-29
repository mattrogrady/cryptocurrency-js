# cryptocurrency-js
This repository currently contains the backend for a cryptocurrency application. This includes a blockchain as well as a synchronized p2p server and API to allow the peers to each have an updated copy of the blockchain.

***Project reference:*** The folder "app" includes the API file, the miner object file, and the peer to peer server class. The folder "blockchain" includes the files that define and test the block objects, as well as the blockchain class that utilizes said block objects. The "wallet" folder contains files that define the user's wallet class, and classes that deal with transactions and the transaction pool. Files in the root such as chain-util and config are utility files used in the application.
