AlgoExecutor

AlgoExecutor is an open-source trading bot that helps execute trading signals by sending them to a private Telegram group.

# Exchange Connectors

AlgoExecutor connectors standardize REST and WebSocket API interfaces to different types of exchanges, enabling you to build sophisticated trading strategies that can be deployed across many exchanges with minimal changes.

### Connector Types

We classify exchange connectors into three main categories:

* **CLOB CEX**: Centralized exchanges with central limit order books that take custody of your funds. Connect via API keys.
  - **Spot**: Trading spot markets
  - **Perpetual**: Trading perpetual futures markets

* **CLOB DEX**: Decentralized exchanges with on-chain central limit order books. Non-custodial, connect via wallet keys.
  - **Spot**: Trading spot markets on-chain
  - **Perpetual**: Trading perpetual futures on-chain

* **AMM DEX**: Decentralized exchanges using Automated Market Maker protocols. Non-custodial, connect via Gateway middleware.
  - **Router**: DEX aggregators that find optimal swap routes
  - **AMM**: Traditional constant product (x*y=k) pools
  - **CLMM**: Concentrated Liquidity Market Maker pools with custom price ranges

## Exchange Connectors

Currently, the master branch of AlgoExecutor also includes the following exchange connectors, which are maintained and updatedd through the AlgoExecutor Foundation governance process. See [Governance](https://algoexecutor.org/governance/) for more information.

| Exchange | Type | Sub-Type(s) | Connector ID(s) | Discount |
|------|------|------|-------|----------|
| [Bybit](https://algoexecutor.org/exchanges/bybit/) | CLOB CEX | Perpetual | `bybit_perpetual` | - |

## Legal

* **License**: AlgoExecutor is open source and Licensed under [Apache 2.0](./LICENSE).
