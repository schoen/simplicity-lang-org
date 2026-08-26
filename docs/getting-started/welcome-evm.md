# Welcome, Ethereum & Solidity Developers

## Welcome to the Bitcoin and Liquid ecosystem.

Simplicity is a [smart contract](../glossary.md#smart-contract) language built for [UTXO-based](../glossary.md#utxo) blockchains like the [Liquid Network](../glossary.md#liquid), which puts it closer to Bitcoin Script than to the EVM's account model. Instead of a contract address holding shared, global state, you build [covenants](../glossary.md#covenant): rules that govern how a specific output can be spent and how state is passed from one UTXO to the next. Primitives like AMMs and limit order books are buildable this way, just structured differently than their EVM equivalents.

The architectural differences from Solidity that matter most: no global state, no reentrancy (there's no shared state to re-enter), and no unbounded loops. Every program's execution cost is statically bounded and known before a transaction is ever broadcast. The language's formal semantics also make it suitable for machine-checked proofs of contract behavior.

## Where to go from here:

* **Perform a live transaction:** Try our [quickstart tutorial](../quickstart/) to make your first Simplicity transaction in minutes.
* **Get introduced to Simplicity from the EVM perspective**: Map your knowledge to our environment by reading our dedicated, detailed [Introduction to Simplicity for EVM Developers](../documentation/simplicity-for-evm-developers), including frequently asked questions and a video presentation on the architectural differences.
* **See it in action:** Explore what's possible with [Simplicity use cases and demos](../../use-cases/), including how complex financial applications are built natively on-chain.
* **Shift your mental model:** Dive into the [UTXO execution model](../../documentation/execution-model) that structures Simplicity contracts and within which they execute on the blockchain. Understand how Simplicity enforces financial logic and spending conditions without global state or account balances.
* **Master state management:** Learn how to pass data from one transaction to another using [covenants and state management](../../documentation/state), the UTXO equivalent to updating contract storage.
* **Connect the outside world:** See how [oracles](../../documentation/oracle) help pass off-chain data into Simplicity contracts.
* **Learn the language:** Dig into <a href="https://github.com/BlockstreamResearch/SimplicityHL/tree/master/examples">simple contract source code</a> that demonstrates SimplicityHL language syntax and features, and <a href="https://github.com/BlockstreamResearch/simplicity-contracts">more complex example contracts</a> with frameworks for running demos. The <a href="https://docs.simplicity-lang.org/documentation/">SimplicityHL language documentation</a> is here when you need it.
* **Connect with the community:** Join our [Telegram group](https://t.me/simplicity_community) or [weekly office hours calls](../../office-hours) to discuss your projects and questions with other adopters and the Simplicity team.
