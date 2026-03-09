# The-Protocol-Experts
Curriculum with Material
# 🧠 Classes & Pedagogical Sequence


# Clase 1 - Presentation, short recap and overview
Students will get an overview of how Bitcoin works at a fundamental level, exploring transactions, UTXOs, mining, and the Bitcoin Core implementation, while building familiarity with the numerical notations used throughout the protocol.

## Topics
-**Mempool explorer**
Herramienta para visualizar las transacciones pendientes de confirmación en la red Bitcoin.
-**Transacciones**
-Mecanismo fundamental por el cual se transfiere valor en Bitcoin entre direcciones.
-**UTXOs, UTXO set**
Las salidas de transacción no gastadas representan el saldo disponible; el UTXO set es el registro global de todos ellos.
-**Transaction Types, Coin selection**
Distintos tipos de transacciones y cómo la wallet elige qué UTXOs usar al construir una transacción.
-**Mining, block height, block depth**
El proceso de minería incorpora transacciones en bloques; la altura y profundidad indican la posición y confirmaciones de un bloque.
-**Bitcoin Core Implementation**
El cliente de referencia que implementa el protocolo Bitcoin y define las reglas de consenso.
-**Notaciones numéricas: binarios, decimal, hexa (0X)**
Los sistemas de numeración usados en Bitcoin: binario, decimal y hexadecimal, fundamentales para leer y codificar datos del protocolo.

## Recommended Material
- [Bitcoin Whitepaper](https://bitcoin.org/files/bitcoin-paper/bitcoin_es.pdf)
- [Video Sistemas numéricos: Binario, Decimal y Hexadecimal](https://www.youtube.com/watch?v=g9-MRBBcvdg)
- [Mastering Bitcoin Chapter 2: How Bitcoin Works](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch02_overview.adoc)
- [¿Cómo funciona Bitcoin?](https://bitcoin.org/es/como-funciona)
- [¿Cómo funcionan las transacciones de Bitcoin?](https://www.bitcoin.com/es/get-started/how-bitcoin-transactions-work/)
- [What is a bitcoin transaction?](https://learnmeabitcoin.com/beginners/guide/transactions/)
- [¿Cómo funciona una transacción de #Bitcoin? ¿Qué es un UTXO, Input, Output?](https://www.youtube.com/watch?v=RM2TGRud01Y)
- [What is a transaction output?](https://learnmeabitcoin.com/beginners/guide/outputs/)
- [Bitcoin Q&A: Unspent Transaction Output (UTXO)](https://www.youtube.com/watch?v=ZCsakXHiwlw)
- [¿Qué es la blockchain de Bitcoin?](https://es.cointelegraph.com/learn/articles/how-does-blockchain-work-a-beginners-guide-to-blockchain-technology)
- [¿Qué es un bloque en blockchain?](https://academy.bit2me.com/que-es-un-bloque-dentro-de-la-blockchain/)
- [¿Qué es una blockchain (cadena de bloques) y cómo funciona?](https://www.criptonoticias.com/criptopedia/blockchain-cadenas-bloques-transacciones-libro-contabilidad-bitcoin-criptomonedas/)


# Clase 2 - Transactions in Depth
Students will dive into the internal structure of Bitcoin transactions, learning how data is represented using Big Endian, Little Endian and Compact Size formats, and analyzing each field of a transaction in detail.

## Topics
-**Big Endian / Little Endian**
Los dos formatos de ordenamiento de bytes usados en Bitcoin; entender cuál se aplica en cada campo es clave para leer correctamente los datos del protocolo.
-**Compact Size**
Formato de entero de longitud variable que Bitcoin usa para ahorrar espacio al representar cantidades como el número de inputs u outputs.
-**TXs - Checking every field (Chapter 6)**
Análisis detallado de cada campo de una transacción Bitcoin: versión, inputs, outputs, locktime y sus respectivos tamaños y formatos.

## Recommended Material
- [Mastering Bitcoin Chapter 6: Transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06_transactions.adoc)
- [What is Endianness? Big-Endian & Little-Endian](https://www.freecodecamp.org/news/what-is-endianness-big-endian-vs-little-endian/)
- [Compact Size](https://learnmeabitcoin.com/technical/general/compact-size/)

 
## Class 3: Wallets & Blocks
Students will explore how Bitcoin wallets work, understanding keys, seeds, passphrases, HD wallets and derivation paths, while also learning how blocks and Merkle trees structure the blockchain.

## Topics
-**Hashes**
Funciones matemáticas que convierten cualquier dato en una cadena de longitud fija; son deterministas, unidireccionales y con efecto avalancha, base de la seguridad en Bitcoin.
-**Keys**
Las claves privadas y públicas que permiten demostrar la propiedad de los fondos y firmar transacciones.
-**Independent / Deterministic / HD Wallets**
Evolución de los tipos de carteras: desde claves independientes hasta carteras jerárquicas deterministas que generan infinitas direcciones desde una sola semilla.
-**Seeds & Passphrases**
La semilla mnemónica (BIP-39) codifica la clave maestra en palabras legibles; la passphrase agrega una capa extra de seguridad generando carteras completamente distintas.
-**Keys Derivation**
Proceso mediante el cual se derivan claves hijas desde la clave maestra siguiendo rutas de derivación estándar (BIP-32, 44, 49, 84).
-**Descriptors**
Estándar que describe de forma explícita qué script y qué claves usar, mejorando la compatibilidad y claridad en la recuperación de carteras.
-**Estructura de bloque**
Composición interna de un bloque Bitcoin: cabecera, transacciones y cómo se encadenan con el bloque anterior.
-**Merkle trees**
Estructura de datos que organiza las transacciones de un bloque y permite verificar eficientemente su inclusión sin descargar todo el bloque.

## Recommended Material
- [Capítulo 5 - Mastering Bitcoin - Wallets](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch05_wallets.adoc)
- [Capítulo 11 - Mastering Bitcoin - The Blockchain](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch11_blockchain.adoc)
- [Bitcoin Transaction Guide - Learn me a Bitcoin](https://learnmeabitcoin.com/beginners/guide/transactions/)
- [Blockstream Explorer](https://blockstream.info/)
- [Bitcoin-cli commands documentation](https://developer.bitcoin.org/reference/rpc/)
- [Choose your Bitcoin wallet](https://bitcoin.org/en/choose-your-wallet?step=1)
- [Cartera HD y Derivation Path, ¿qué son?](https://estudiobitcoin.com/cartera-hd-y-derivation-path-que-son/)
- [Wordlists BIP-39](https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md)
- [Hardware Wallets](https://btctranscripts.com/es/austin-bitcoin-developers/2019-06-29-hardware-wallets)
- [So you want to build a Bitcoin HD wallet?](https://medium.com/bitcraft/so-you-want-to-build-a-bitcoin-hd-wallet-part-1-8b27aa001ac3)
- [Mnemonic phrase](https://bitcoinwiki.org/wiki/mnemonic-phrase)
- [Bitcoin Q&A: How Do Mnemonic Seeds Work?](https://www.youtube.com/watch?v=wWCIQFNf_8g)


# Clase 4 - Transaction Fees, Mining & Consensus
Students will understand how transaction fees are calculated and how they influence confirmation priority, as well as how the mining process and consensus mechanism allow the network to agree on a single valid chain.

## Topics
-**Transaction Fees**
Cómo se calculan las comisiones de las transacciones Bitcoin, por qué son necesarias y cómo afectan la prioridad de confirmación en la mempool.
-**Mining and Consensus**
El proceso de minería que incorpora transacciones en bloques y el mecanismo de consenso que permite a la red acordar el estado de la cadena de bloques.

## Recommended Material
- [Mastering Bitcoin Capítulo 9 - Transaction Fees](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch09_fees.adoc)
- [Mastering Bitcoin Capítulo 12 - Mining and Consensus](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch12_mining.adoc)
- [Qué hacer si tu transacción Bitcoin no se confirma](https://estudiobitcoin.com/que-hacer-si-tu-transaccion-bitcoin-no-se-confirma/)
- [Difficulty](https://learnmeabitcoin.com/technical/mining/target/)
- [¿Qué es un bloque huérfano?](https://academy.bit2me.com/que-es-un-bloque-huerfano/)
- [¿Qué es un Fork en Blockchain?](https://academy.bit2me.com/que-es-un-fork-en-blockchain/)


## Final Project & Assessment
Students demonstrate their understanding by applying course concepts in a research paper, case study, or practical project.

**Assessment & Evaluation:**
- Weekly Quizzes & Assignments (40%) – Reinforce key theoretical concepts
- Midterm Exam (20%) – tbd
- Final Project (40%) – tbd Sonnet 4.6
