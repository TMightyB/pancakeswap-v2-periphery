# PancakeSwap V2 Periphery Interfaces

This directory contains the interface contracts that are part of the PancakeSwap V2 Periphery. These interfaces define the functions and structures that the PancakeSwap protocol utilizes for interacting with liquidity pools and executing trades.

## Table of Contents

- [Overview](#overview)
- [Interfaces](#interfaces)
- [Usage](#usage)
- [License](#license)

## Overview

PancakeSwap uses the Ethereum-based automated market maker model for trading tokens. The V2 Periphery interfaces are essential for developers building dApps that integrate with the PancakeSwap protocol, allowing interactions with liquidity pools, swaps, and additional functionality.

## Interfaces

The following interfaces are included in this folder:

- **IPancakeRouter02.sol**: The main routing interface that includes swap and liquidity functions.
- **IPancakeFactory.sol**: The factory interface for creating new liquidity pools.
- **IPancakePair.sol**: The interface for interacting with liquidity token pairs and accessing pool data.
- **ITransferHelper.sol**: A utility interface that aids in safe token transfers.

Each of these interfaces provides functions and events that facilitate the core operations of the PancakeSwap protocol, enabling developers to build around its functionalities.

## Usage

To use these interfaces in your smart contracts or JavaScript code, you should include them as follows:

### In Solidity

Include the interfaces in your Solidity contracts:

```solidity
import './path/to/IPancakeRouter02.sol';
import './path/to/IPancakeFactory.sol';
import './path/to/IPancakePair.sol';
import './path/to/ITransferHelper.sol';
