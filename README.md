# b2-account-infra

## Design

[https://github.com/b2network/b2-account-infra/issues/1](https://github.com/b2network/b2-account-infra/issues/1)

## Repositories

[aa-core](https://github.com/b2network/aa-core): forked from eth-infinitism/account-abstraction v0.6.0

[aa-account-kernel](https://github.com/b2network/aa-account-kernel): smart contract account forked from zerodevapp/kernel

[aa-deploy](https://github.com/b2network/aa-deploy): deployment scripts for AA related contracts using Foundry

[aa-bundler](https://github.com/b2network/aa-bundler): forked from etherspot/skandha

[aa-sdk](https://github.com/b2network/aa-sdk): forked from zerodevapp/sdk

[aa-demos](https://github.com/b2network/aa-demos): examples for aa-sdk usage

## Published NPM packages (hosted on Github Package)

- @b2network/aa-core: artifacts for AA core contracts
- @b2network/aa-account-kernel: artifacts for Kernel contracts
- @b2network/aa-sdk: TS SDK to interact with Kernel accounts

## Deployed Contracts

### b2-zkevm-dev (1002)

| name | address |
| ---- | ------- |
| EntryPoint | 0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789 |
| KernelFactory | 0x7516283Ff7090B8286E23a16f8b5b35B3ba541A2 |
| KernelImplementation | 0x277A60Fe8b476df00295ed8D89aFca39F7f73187 |
| SimpleWeightedECDSAValidator | 0xbf50c52aA54aB01a6a38ac7b4475bdF04e768319 |
| SCARegistry | 0x231aec684Ad0e63c2F4d176EddCE97A1B666247c |
| VerifyingPaymaster | 0xaD22dd55f343220c634AB94Db20e3C184faAeEB7 |

## Deployed Services

### b2-zkevm-dev (1002)

| name | url |
| ---- | --- |
| AA Bundler | <http://43.157.191.32:14337> |
| Paymaster Signing Service | <http://43.157.191.32:14338> |
