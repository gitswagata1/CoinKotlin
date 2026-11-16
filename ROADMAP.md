# Roadmap

## Vision

The clearest possible Kotlin implementation of how a UTXO blockchain works, suitable for teaching.

## Milestones

### Now

- [ ] Add unit tests for hashing, signing, mining and chain validation
- [ ] Add a Gradle build so `./gradlew run` and `./gradlew test` work
- [ ] Reject double-spends and invalid signatures with explicit tests

### Next

- [ ] Configurable difficulty with automatic adjustment
- [ ] Merkle tree of transactions per block
- [ ] Mining rewards and transaction fees

### Later

- [ ] Peer-to-peer node with a simple REST API
- [ ] Persist the chain to disk
- [ ] Interactive CLI wallet

## Where this can go

| Direction | Idea |
| --------- | ---- |
| **Education** | A step-by-step tutorial and slide deck that builds the chain one concept per commit. |
| **Publication** | A short article explaining UTXO validation with runnable Kotlin examples. |

## How to help

See [CONTRIBUTING.md](CONTRIBUTING.md) and the issues labelled `good first issue`.
