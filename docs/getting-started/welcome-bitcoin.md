# Welcome, Bitcoin Developers

## Welcome to the next evolution of building on Bitcoin.

If you know [Bitcoin Script](../glossary.md#bitcoin-script), you know its constraints: a small, deliberately limited opcode set, no loops, and no built-in way to enforce rules across more than one transaction. [Simplicity](../glossary.md#simplicity) targets the same UTXO model and the same Bitcoin-style transaction semantics, but is built on a small set of functional [combinators](../glossary.md#combinator) instead of an opcode set. It adds [introspection](../glossary.md#introspection), so a program can constrain a transaction's outputs and not just check signatures, which is what makes [covenants](../glossary.md#covenant) and multi-transaction [vault](../glossary.md#vault) protocols possible without the workarounds Script requires today. Every program's execution cost is still statically bounded and known before you fund it, the same guarantee you already rely on in Script.

Simplicity offers you tools to represent and enforce complex financial agreements and instruments as on-chain [smart contracts](../glossary.md#smart-contract), in line with Bitcoin architecture and philosophy. And the [SimplicityHL](../glossary.md#simplicityhl) language lets you write this logic in a familiar and highly readable Rust-like syntax.

## Where to go from here:

* **Deploy your first smart contract:** Try our [quickstart tutorial](../quickstart/) to make your first Simplicity transaction ("pay-to-public-key" implemented in SimplicityHL) in minutes.
* **Beyond Bitcoin Script:** See how Simplicity programs define execution conditions within the [UTXO model](../../documentation/execution-model) you already know, but with major new capabilities like [introspection](../glossary.md#introspection).
* **Unlock new primitives:** Learn to build programmatic vaults and advanced constraints by reading up on [covenants and state management](../../documentation/state) and [oracles](../../documentation/oracle) in Simplicity. Check how [jets](../../documentation/jets) expose transaction details and efficiently perform complex calculations.
* **See what's possible:** Explore what Simplicity can do with [Simplicity use cases and demos](../../use-cases/).
* **Learn the language:** Dig into <a href="https://github.com/BlockstreamResearch/SimplicityHL/tree/master/examples">simple contract source code</a> that demonstrates SimplicityHL language syntax and features, and <a href="https://github.com/BlockstreamResearch/simplicity-contracts">more complex example contracts</a> with frameworks for running demos. The <a href="https://docs.simplicity-lang.org/documentation/">SimplicityHL language documentation</a> is here when you need it.
* **Connect with the community:** Join our [Telegram group](https://t.me/simplicity_community) or [weekly office hours calls](../../office-hours) to discuss your projects and questions with other adopters and the Simplicity team.
