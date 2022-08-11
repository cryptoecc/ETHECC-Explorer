# ETHECC-Explorer

<!-- project logo w/ quick links -->
<p align="center">
  <img src="https://github.com/etclabscore/jade-media-assets/blob/master/j-explorer/j-explorer(PNG)/128x128.png?raw=true" />


</p>
<center>
![logo](https://https://github.com/istiaque010/expeditionexplorer/blob/main/img3.PNG?raw=true)

  <h3 align="center">ETHECC-Explorer</h3>

  <p align="center">
    A block explorer for the Ethereum Stack.
    <br />
    <a href="http://3.39.29.150:3000/?network=ETH-ECC">View Demo</a>
    ·
    <a href="">Report Bug</a>
    ·
    <a href="">Request Feature</a>
  </p>
</center>

![expedition_gif](https://user-images.githubusercontent.com/364566/94349388-d17fb000-fff8-11ea-92ae-71c002474a65.gif)

<!-- table of contents -->
## Table of Contents
  - [About The Project](#about-the-project)
  - [Getting Started](#getting-started)
      - [Prerequisites](#prerequisites)
      - [Installation](#installation)
- [Usage](#usage)
  - [Start explorer](#start-the-explorer)
  - [Configurations](#configurations)
- [Contributing](#contributing)
- [Resources](#resources)

<!-- about the project -->
## About The Project

[Expedition](https://expedition.dev) is a minimal block explorer for Ethereum Stack. It does not use a database, and can be configured to point at any remote RPC node for any EVM-based network. The goal of the Explorer is to provide a resource for network information and block exploration with only an Ethereum EPC endpoint.

Explorer Features:
- Display chain id
- Syncing status
- Runtime configuration for endpoints
- Search by Block, Transaction, Address
- Charts for hash, transaction count, gas used, uncles
- Preview latest blocks with pagination
- Multi-language support

<!-- getting started with the project -->
## Getting Started
### Prerequisites
- node `v10.15.3` or later
- npm `v6.4.1` or later

### Installation
Clone/ download the project, and install dependencies.
```bash
git clone https://github.com/xops/expedition.git && cd expedition && npm install
```

<!-- example usage, screen shots, demos -->
## Usage

### Start the explorer
```bash
npm start
```
*The explorer will run at http://localhost:3000/.*

### Configurations

#### Set rpc via url

`?rpcUrl=` Set custom rpc url.

Example:

http://localhost:3000/?rpcUrl=https://www.ethercluster.com/kotti

#### Configure default urls via environment variables

Override eth url

```
REACT_APP_ETH_RPC_URL=https://www.ethercluster.com/kotti npm start
```

<!-- template just leave alone  -->
## Roadmap
See the [open issues](https://github.com/etclabscore/xops/issues) for a list of proposed features (and known issues).

<!-- template just leave alone  -->
## Contributing
How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.

## License
Apache License 2.0

<!-- references and additional resources  -->
## Resources
- [OpenRPC](https://open-rpc.org)

---
*This repo originally forked from [ETCDEVTeam/emerald-explorer](https://github.com/ETCDEVTeam/emerald-explorer).*
