# Web3 Interview Preparation

- [Web3 Interview Preparation](#web3-interview-preparation)
  - [Web3 Questions (& Answers)](#web3-questions--answers)
    - [Basics](#basics)
    - [Blockchain and Blockchain alternatives](#blockchain-and-blockchain-alternatives)
    - [Cryptography](#cryptography)
    - [Attacks](#attacks)
    - [Ethereum](#ethereum)

## Web3 Questions (& Answers)

### Basics

<details>
  <summary>What is Web1?</summary>
    <ul>
      <li>
        Web1 was the first phase of the internet. Most participants were consumers
        of content. It was all about serving static content instead of dynamic HTML.
      </li>
    </ul>
</details>
<details>
  <summary>What is Web2?</summary>
    <ul>
      <li>
        You can think of Web2 as the interactive and social web.
      </li>
    </ul>
</details>
<details>
  <summary>What is Web3?</summary>
    <ul>
      <li>
        I'd it call it the decentralized internet. It provides native built-in payments while still being self-governing
      </li>
    </ul>
</details>
<details>
  <summary>What is consensus?</summary>
    <ul>
      <li>
        Consensus is the agreement on what (usually transactions) has happened and what has not
      </li>
    </ul>
</details>
<details>
  <summary>What is decentralization?</summary>
    <ul>
      <li>
        Decentralisation is the opposite of centralisation and means that something like power, control or trust is not focused on just a few people, but is distributed among many or even all of them.
      </li>
    </ul>
</details>
<details>
  <summary>What is a decentralized ledger?</summary>
    <ul>
      <li>
        I would describe it as a database that gets save from a group of people and is updated in regular blocks of time
      </li>
    </ul>
</details>
<details>
  <summary>What is a DAO?</summary>
    <ul>
      <li>
        DAO is an acronym for Decentralized Autonomous Organization
      </li>
      <li>
        Is an organization that’s governed by code instead of leaders
      </li>
      <li>
        DAO in its simplest for can be described as a group chat with a shared bank account
      </li>
    </ul>
</details>
<details>
  <summary>What is the difference between an NFT and a fungible token?</summary>
    <ul>
      <li>
        NFTs are unique digital asset like artworks and collectibles. Non fungible tokens are not interchangeable
      </li>
      <li>
        FungibleTokens like Ether or Bitcoin on the other hand are divisible and replaceable
      </li>
    </ul>
</details>
<details>
  <summary>What is the difference between a coin an a token?</summary>
    <ul>
      <li>
        Sometimes people use the term "coin" and "token" interchangeably. However, there are very big differences between crypto coins and crypto tokens
      </li>
      <li>
        A digital coin is an asset that is native to its own blockchain. (BTC, ETH, ...)
      </li>
      <li>
        Tokens are created on existing blockchains (all ERC-20 tokens, ...)
      </li>
    </ul>
</details>
<details>
  <summary>What is the difference between layer 1 and layer 2 networks?</summary>
    <ul>
      <li>
        A layer 1 network describes the underlying "main" blockchain that is the ultimately source of truth and is responsible for the settlement of transactions
      </li>
      <li>
        Layer 2 networks extend the functionality of their layer 1 counterpart. For example increase the transaction speed or lower transaction costs. A layer-2 solution is not a blockchain! (e.g Arbitrum for Ethereum)
      </li>
      <li>
        Hint: Layer 1 solutions without scaling limitations usually don't need scaling solutions
      </li>
    </ul>
</details>
<details>
  <summary>What is a side chain?</summary>
    <ul>
      <li>
        A side chain is essentially just a blockchain that is linked to another main blockchain. (e.g Liquid Network for Bitcoin, Polygon for Ethereum)
      </li>
    </ul>
</details>
<details>
  <summary>What is DeFi?</summary>
    <ul>
      <li>
        DeFi is an acronym for decentralized finance
      </li>
      <li>
        It is an umbrella term for peer-to-peer financial services
      </li>
      <li>
        Typical services include earning interest, borrowing and lending crypto
      </li>
    </ul>
</details>
<details>
  <summary>What is a crypto wallets?</summary>
    <ul>
      <li>
        Crypto wallets store your private key and lets you allowing you to send and receive cryptocurrencies
      </li>
      <li>
        Crypto wallets technically don’t store your crypto! If you lose your private keys, you lose access to your money and not the money itself
      </li>
    </ul>
</details>
<details>
  <summary>Bring the terms "decentralization", "bitcoin", "crypto currency", "consensus" and "blockchain" in an order. (broad to specific)</summary>
    <ul>
      <li>
        Consensus -> decentralization -> blockchain -> crypto currency -> bitcoin
      </li>
    </ul>
</details>
<details>
  <summary>What are dApps?</summary>
    <ul>
      <li>
        Decentralized applications (dApps) are digital applications that exist and run on a peer to peer(P2P) network of computers instead of a single computer
      </li>
    </ul>
</details>

### Blockchain and Blockchain alternatives

<details>
  <summary>What is a blockchain?</summary>
    <ul>
      <li>
        a blockchain is a digital file consisting of files that is consistently growing. all records are linked together using cryptography. blocks contain information about the block previous to it. For a blockchain to be decentralised it has to be distributed to group of people and it has to be updated in regular blocks of time
      </li>
      <li>
        blockchains are resistant to modification of their data
      </li>
    </ul>
</details>
<details>
  <summary>Why are blockchains resistant to modification of their data?</summary>
    <ul>
      <li>
        Because once recorded, the data in any given block cannot be altered retroactively without altering all subsequent blocks
      </li>
    </ul>
</details>
<details>
  <summary>Tell me the three factors of the blockchain trillema?</summary>
    <ul>
      <li>
        security, decentralization, and scalability -> you can only choose two!
      </li>
    </ul>
</details>
<details>
  <summary>What problem does a blockchain solve?</summary>
    <ul>
      <li>
        How can I save a digital information in a immutable way without a centralised authority
      </li>
    </ul>
</details>
<details>
  <summary>Explain a blockchain alternative</summary>
    <ul>
      <li>
       Directed Acyclic Graph (DAG), dag transaction are linked to one and another directly instead of being group and processed in blocks. This makes dags more scalable than blockchains in theory
      </li>
    </ul>
</details>
<details>
  <summary>Can you “hide” a transaction on a blockchain?</summary>
    <ul>
      <li>
        Transaction can't be hidden. All transactions are visible to everyone
      </li>
    </ul>
</details>
<details>
  <summary>Where are transactions stored in a blockchain?</summary>
    <ul>
      <li>
        In a blockchain, transactions are stored in a "block" of a public ledger
      </li>
    </ul>
</details>
<details>
  <summary>What is a Miner?</summary>
    <ul>
      <li>
       Miners are nodes, who receive rewards for verifying transactions and marinating network integrity
      </li>
    </ul>
</details>

### Cryptography

<details>
  <summary>What is a merkle root? (BTC)</summary>
    <ul>
      <li>
       The merkle root it the root hash of a merkle tree. The merkle root is put into the block header of a block
      </li>
    </ul>
</details>
<details>
  <summary>What role do transactions play in a merkle tree?</summary>
    <ul>
      <li>
        In a merkle tree, the the transaction hashes are considered the leaves. Each non-leaf node (branch) is a hash of its child hashes
      </li>
    </ul>
</details>
<details>
  <summary>Why are merkle trees so important?</summary>
    <ul>
      <li>
        If Bitcoin didn’t have Merkle Trees, every node on the network would need to maintain a full copy of every transaction that has ever happened on Bitcoin
      </li>
    </ul>
</details>

### Attacks

<details>
  <summary>What is a 51% attack?</summary>
    <ul>
      <li>
        If the hacker is able to control 51% or more of the nodes, it will gain control over the entire network
      </li>
    </ul>
</details>

### Ethereum

<details>
  <summary>What is Ethereum?</summary>
    <ul>
      <li>
        Ethereum is a decentralized, open-source blockchain with smart contract functionality.
      </li>
    </ul>
</details>
<details>
  <summary>What is Ether?</summary>
    <ul>
      <li>
        Ether is Ethereum’s native cryptocurrency for the Ethereum platform
      </li>
    </ul>
</details>
<details>
  <summary>How does Ethereum differ from Bitcoin?</summary>
    <ul>
      <li>
        Ethereum utilizes blockchain technology not only for maintaining a decentralized payment network but also for storing computer code that can be used to power tamper-proof decentralized financial contracts and applications
      </li>
    </ul>
</details>
<details>
  <summary>What are smart contracts?</summary>
    <ul>
      <li>
        Smart contract are computer code that when deployed onto the Ethereum platform run when predetermined conditions are met. The code can not be updated or deleted once deployed
      </li>
    </ul>
</details>
<details>
  <summary>What is the EVM?</summary>
    <ul>
      <li>
        EVM is an acronym for Ethereum Virtual Machine
      </li>
      <li>
        EVM acts like a global computer that lends its accumulated computing power to developers
      </li>
      <li>
        The EVM can be accessed from anywhere in the world through participating Ethereum nodes
      </li>
    </ul>
</details>
<details>
  <summary>What is a node in Ethereum?</summary>
    <ul>
      <li>
        A node is a computer connected to the network, which is responsible for processing transactions
      </li>
    </ul>
</details>
<details>
  <summary>How can you connect with a node?</summary>
    <ul>
      <li>
        You can connect to a node by WS-RPC, JSON-RPC, and IPC-RPC
      </li>
    </ul>
</details>
<details>
  <summary>Which consensus mechanism does Ethereum use?</summary>
    <ul>
      <li>
        Ethereum currently uses proof of Work but plans to use proof of stake in Ethereum 2.0
      </li>
    </ul>
</details>
<details>
  <summary>Which programming language is used to write smart contracts?</summary>
    <ul>
      <li>
        Solidity is the primary programming language used for writing smart contracts and dApps
      </li>
    </ul>
</details>
<details>
  <summary>How does Proof of Work work?</summary>
    <ul>
      <li>
        The central principle behind PoW consensus is to solve a complex mathematical problem. The first miner to find the right solution, advertise it to the whole network, and receive a reward in cryptocurrency provided by the protocol
      </li>
      <li>
        The disadvantage is that it requires a lot of computational power
      </li>
    </ul>
</details>
<details>
  <summary>How does Proof of Stake work?</summary>
    <ul>
      <li>
        It is a cryptocurrency consensus mechanism
      </li>
      <li>
        Proof of Stake tries to deal with the main drawback of PoW
      </li>
      <li>
        The central principle behind PoS consensus is that cryptocurrency owners can stake their crypto. From this so called "validators" one then is selected randomly to "mint" a new block. The more coins a person stakes, the higher is the chance to be selected
      </li>
    </ul>
</details>
<details>
  <summary>List common smart contract standards</summary>
    <ul>
      <li>
        ERC-20: Token Standard
      </li>
      <li>
        ERC-165: A standard to publish and detect what interfaces a smart contract implements.
      </li>
      <li>
        ERC-721: Non-fungible token standard
      </li>
      <li>
        ERC-1155: Multi-token standard
      </li>
    </ul>
</details>
<details>
  <summary>How can you obtain Ether?</summary>
    <ul>
      <li>
        Ethers can be obtained by mining or by trading Ethers with other cryptocurrencies
      </li>
    </ul>
</details>
<details>
  <summary>What are the types of Ethereum networks that exist?</summary>
    <ul>
      <li>
        Mainnet
      </li>
      <li>
        Testnets: Ropsten, Goerli, Kovan, Rinkeby
      </li>
      <li>
        Local networks
      </li>
    </ul>
</details>
<details>
  <summary>Why is Gas Fees taken?</summary>
    <ul>
      <li>
        The creation of consensus in a decentralised system must cost something, because it motivates all participants to save the optimal reality
      </li>
    </ul>
</details>
<details>
  <summary>Why should a developer define a solidity version at the beginning of a file?</summary>
    <ul>
      <li>
        It reduces incompatibility glitches that can occur while compiling with another version
      </li>
    </ul>
</details>
<details>
  <summary>How can the transaction fees be calculated?</summary>
    <ul>
      <li>
        Gas Limit \* Gas Price (Wei)
      </li>
    </ul>
</details>
<details>
  <summary>What is an ABI?</summary>
    <ul>
      <li>
        ABI is an acronym for Application Binary Interface
      </li>
      <li>
        The ABI is needed to access the bytecode (contracts are stored as bytecode on the blockchain)
      </li>
      <li>
        The ABI defines which function you can invoke
      </li>
      <li>
        It can be generated from your smart contract
      </li>
    </ul>
</details>
<details>
  <summary>How are smart contracts stored into the blockchain?</summary>
    <ul>
      <li>
        They are stored as bytecode (=binary data) under a specific address also known as contract address
      </li>
    </ul>
</details>