# melon-protocol-subgraph
This is the subgraph, a collection of GraphQL schemas and mappings that parse the events broadcast by the Melon Protocol on the Ethereum blockchain.

Melon is an Ethereum-based protocol for decentralized on-chain asset management. It is a protocol for people or entities to manage their wealth & the wealth of others within a customizable and safe environment. Melon empowers anyone to set up, manage and invest in customized on-chain investment vehicles.

Our smart contracts can be found in this repository https://etherscan.io/address/0xec67005c4e498ec7f55e092bd1d35cbc47c91892#code.

# Development
Before you can build, create and deploy this subgraph, you have to execute the following commands in the terminal:

$ yarn install

$ yarn prepare:mainnet

The first command installs all external dependencies, while the latter generates the subgraph.yaml file, which is required by The Graph.

The manual how to deploy Subgraph you can find here https://colliseum2006-23245.medium.com/как-быстро-задеплоить-subgraph-пошаговый-чеклист-функций-в-power-shell-a8f4741c6288
