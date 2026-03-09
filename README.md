# The-Protocol-Experts
Curriculum with Material
# 🧠 Classes & Pedagogical Sequence

## Class 1: Presentation, short recap and overview
Review objectives of the lesson, what students will learn, use the topic list,  why it is important to learn how Bitcoin works.


## Topics 
- **Bitcoin Script and its purpose:**  How it functions as a stack-based, deterministic, and non-Turing complete programming language.
- **Structure of a script:** The difference between ScriptPubKey and ScriptSig in a Bitcoin transaction.
- **Essential OP_CODES:** Introduction to key operation codes such as OP_DUP, OP_HASH160, OP_EQUALVERIFY, OP_CHECKSIG, and more.
- **Common use cases:** From P2PKH addresses to more advanced scripts like P2SH and multisig.
- **Limitations and security:** Bitcoin Script's constraints to prevent attacks and execution errors.


## Material 
- Lectura 1:  [Mastering Bitcoin Chapter 2: How Bitcoin Works](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch02_overview.adoc)
- Lectura 2:  [Mastering Bitcoin Chapter 3: Bitcoin Core, the reference implementation](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch03_bitcoin-core.adoc)
- Video [Sistemas numéricos: Binario, Decimal y Hexadecimal](https://www.youtube.com/watch?v=g9-MRBBcvdg)
- Lectura 3:  [What is a transaction output](https://learnmeabitcoin.com/beginners/guide/outputs/)
- Video:  [Bitcoin Q&A: Unspent Transaction Output (UTXO)](https://www.youtube.com/watch?v=ZCsakXHiwlw)



## Class 2: Bitcoin Transactions & Multi-Sig Scripts
Students take a deep dive into how Bitcoin transactions work, analyzing their structure and how inputs and outputs are validated. They will also explore multi-signature (multi-sig) scripts, learning how to create and interpret them.

## Topics
- **Structure of a Bitcoin transaction:** Inputs, outputs, UTXOs, and transaction serialization.
- **Transaction verification:** How nodes validate transactions using Bitcoin Script.
- **Multi-signature scripts:** Understanding OP_CHECKMULTISIG and how multi-sig transactions work.
- **Writing basic multi-sig scripts:** Creating and interpreting P2SH multi-sig transactions.
- **Security considerations:** The benefits and trade-offs of multi-signature setups.

 ## Material
- Lectura 1: [Mastering Bitcoin Chapter 6: Transaction](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06_transactions.adoc)
- Video: [Bitcoin & SHA-256 Explicados con Animaciones](https://www.youtube.com/watch?v=d_-UNZ4umBg)
- Lectura 2: [What is Endianness? Big-Endian & Little-Endian](https://www.geeksforgeeks.org/dsa/little-and-big-endian-mystery/)
- Lectura 3: [Compact Size](https://learnmeabitcoin.com/technical/general/compact-size/)
- Lectura 4: [Merkle root / Merkle tree](https://learnmeabitcoin.com/technical/block/merkle-root/)

 
## Class 3: Hashlocks, Timelocks & Conditional Logic
Students will explore advanced scripting techniques that enable conditional transactions in Bitcoin. They will learn how hashlocks and timelocks work, allowing transactions to be locked by time or secret values, and how to implement them using Bitcoin Script.

## Topics
- **Conditional transactions:** How Bitcoin Script enforces spending conditions.
- **Hashlocks:** Using OP_HASH160 and preimages to lock transactions until a secret is revealed.
- **Timelocks:**  Implementing time-based restrictions with OP_CHECKLOCKTIMEVERIFY (CLTV) and OP_CHECKSEQUENCEVERIFY (CSV).
- **Practical applications:** Use cases like atomic swaps, Lightning Network, and payment channels.
- **Security considerations:** Best practices for safely implementing conditional logic in scripts.

## Material
- Lectura 1: [Mastering Bitcoin Capítulo 6 - Wallet Recovery](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch05_wallets.adoc)
- Lectura 2: [Mastering Bitcoin Capítulo 11 - The Blockchain](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch11_blockchain.adoc)
### Material extra recomendado: 
- [Bitcoin & SHA-256 Explicados con Animaciones](https://www.youtube.com/watch?v=d_-UNZ4umBg) 
- [Merkle root / Merkle tree](https://learnmeabitcoin.com/technical/block/merkle-root/)
- [Cartera HD y Derivation Path, ¿qué son?](https://estudiobitcoin.com/cartera-hd-y-derivation-path-que-son/)
- [How Do Mnemonic Seeds Work?](https://www.youtube.com/watch?v=wWCIQFNf_8g)


## Class 4: Debugging & Real-World Use Cases
Students will learn how to debug Bitcoin scripts using specialized tools and techniques. They will also explore real-world applications of Bitcoin Script, analyzing how different OP_CODES are used in actual transactions and smart contract-like constructions on Bitcoin.

## Topics
- **Debugging Bitcoin scripts:** Tools and methods for testing and troubleshooting scripts.
- **Script execution analysis:** How to interpret stack operations and debug failures.
- **Real-world use cases:**  Examining how scripts are used in P2SH, multi-sig, and Lightning Network.
- **Simulating transactions:** Using testnets and scripting environments to build and analyze Bitcoin transactions.
- **Best practices and security:**  Avoiding common mistakes and ensuring robustness in Bitcoin scripting.

## Material
- Lectura 1: [Mastering Bitcoin Capítulo 9 - Transaction Fees](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch09_fees.adoc)
- Lectura 2: [Mastering Bitcoin Capítulo12 - Mining and Consensus](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch12_mining.adoc)
### Material extra recomendado: 
- [Qué hacer si tu transacción Bitcoin no se confirma](https://estudiobitcoin.com/que-hacer-si-tu-transaccion-bitcoin-no-se-confirma/)
- [Difficulty](https://learnmeabitcoin.com/beginners/guide/difficulty/)
- [¿Qué es un bloque huérfano?](https://academy.bit2me.com/que-es-un-bloque-huerfano/)
- [¿Qué es un Fork en Blockchain?](https://onekey.so/blog/es/ecosystem/what-is-a-blockchain-fork-soft-vs-hard-forks-explained/)




## 📝 Final Project & Assessment

- **Weekly Quizzes & Assignments (40%)** – Reinforce key theoretical concepts  
- **Midterm Exam (20%)** – *To be defined*  
- **Final Project (40%)** – *To be defined*
