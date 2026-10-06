# EEZ Specifications

This site contains three separate specifications:

- [EEZ Protocol](eez-protocol-spec/index.md) defines the shared cross-chain framework.
- [Rollup0](rollup0-spec/index.md) defines the open-composer EEZ network that settles on Ethereum.
- [Gnosis Chain](gnosis-chain-spec/index.md) defines the authorized-sequencer variant of Rollup0.

The informative [Implementations](implementations/index.md) chapter compares known client
implementations with these specifications.

Rollup0 imports EEZ. Gnosis Chain imports EEZ and Rollup0, then replaces only the block-production
authorization rule.
