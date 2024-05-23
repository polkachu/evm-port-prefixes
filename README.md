# EVM Port Prefixes

## Rationale

Node operators in the EVM ecosystem often wants to run multiple EVM based nodes on the sames server to save cost.

This project is an attempt to standardize these ports while avoiding port conflict. While any random non-conflicting ports can do, a standardized port prefix system can make the port assignment more predictable.

This project is intended for Polkachu team's internal us. That said, if other node operators follow the same system, we can easily exchange deployment scripts without breaking codes.

## Supported EVMs and Prefixes

| Network  | Port Prefix |
| -------- | ----------- |
| Ethereum | 100         |
| Optimism | 101         |
| Arbitrum | 102         |
| Base     | 103         |

## JSON API

Here is the [JSON API](https://raw.githubusercontent.com/PolkachuIntern/evm-port-prefixes/master/networks.json).
