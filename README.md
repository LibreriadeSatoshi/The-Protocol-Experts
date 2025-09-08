# The-Protocol-Experts
Curriculum with Material
# 🧠 Classes & Pedagogical Sequence

## Class 1: Introduction to Bitcoin Script & Basic OP_CODES
Students begin by understanding the fundamentals of Bitcoin Script, its role in the Bitcoin network, and how it enables custom transaction validation conditions without the need for trusted third parties.

##Topics##
- **Bitcoin Script and its purpose:** Stack-based, deterministic, non-Turing complete language.
- **Structure of a script:** ScriptPubKey vs ScriptSig.
- **Essential OP_CODES:** OP_DUP, OP_HASH160, OP_EQUALVERIFY, OP_CHECKSIG, etc.
- **Common use cases:** P2PKH, P2SH, multisig.
- **Limitations and security:** Constraints to prevent attacks and execution errors.

## Material##
Lectura 1:  [Mastering Bitcoin Chapter 2: How Bitcoin Works](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch02_overview.adoc)
Lectura 2:  [Mastering Bitcoin Chapter 3: Bitcoin Core, the reference implementation](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch03_bitcoin-core.adoc)
Video [Sistemas numéricos: Binario, Decimal y Hexadecimal](https://www.youtube.com/watch?v=g9-MRBBcvdg)
Lectura 3:  [What is a transaction output](https://learnmeabitcoin.com/beginners/guide/outputs/)
Video:  [Bitcoin Q&A: Unspent Transaction Output (UTXO)](https://www.youtube.com/watch?v=ZCsakXHiwlw)


## Class 2: Bitcoin Transactions & Multi-Sig Scripts
Students take a deep dive into how Bitcoin transactions work, analyzing their structure and how inputs and outputs are validated. They will also explore multi-signature (multi-sig) scripts, learning how to create and interpret them.

##Topics##
- **Structure of a Bitcoin transaction:** Inputs, outputs, UTXOs, serialization.
- **Transaction verification:** Node validation via Bitcoin Script.
- **Multi-signature scripts:** OP_CHECKMULTISIG and multi-sig logic.
- **Writing basic multi-sig scripts:** P2SH multi-sig transactions.
- **Security considerations:** Benefits and trade-offs.

 ## Material##
Lectura 1: [Mastering Bitcoin Chapter 6: Transaction](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06_transactions.adoc)
Video: [Bitcoin & SHA-256 Explicados con Animaciones](https://www.youtube.com/watch?v=d_-UNZ4umBg)
Lectura 2: [What is Endianness? Big-Endian & Little-Endian](https://www.geeksforgeeks.org/dsa/little-and-big-endian-mystery/)
Lectura 3: [Compact Size](https://learnmeabitcoin.com/technical/general/compact-size/)
Lectura 4: [Merkle root / Merkle tree](https://learnmeabitcoin.com/technical/block/merkle-root/)

 
## Class 3: Hashlocks, Timelocks & Conditional Logic
Students will explore advanced scripting techniques that enable conditional transactions in Bitcoin. They will learn how hashlocks and timelocks work, allowing transactions to be locked by time or secret values, and how to implement them using Bitcoin Script.

##Topics##
- **Conditional transactions:** Enforcing spending conditions.
- **Hashlocks:** OP_HASH160 and preimages.
- **Timelocks:** OP_CHECKLOCKTIMEVERIFY (CLTV) and OP_CHECKSEQUENCEVERIFY (CSV).
- **Practical applications:** Atomic swaps, Lightning Network, payment channels.
- **Security considerations:** Best practices.

## Material##




## Class 4: Debugging & Real-World Use Cases
Students will learn how to debug Bitcoin scripts using specialized tools and techniques. They will also explore real-world applications of Bitcoin Script, analyzing how different OP_CODES are used in actual transactions and smart contract-like constructions on Bitcoin.

##Topics##
- **Debugging Bitcoin scripts:** Tools and techniques.
- **Script execution analysis:** Stack operations and failure debugging.
- **Real-world use cases:** P2SH, multisig, Lightning Network.
- **Simulating transactions:** Testnets and scripting environments.
- **Best practices and security:** Robust scripting.

## 📝 Final Project & Assessment

- **Weekly Quizzes & Assignments (40%)** – Reinforce key theoretical concepts  
- **Midterm Exam (20%)** – *To be defined*  
- **Final Project (40%)** – *To be defined*
