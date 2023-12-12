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

## Published Go modules (public)

- github.com/b2network/b2-go-aa-utils

## Deployed Contracts

### b2-zkevm-dev (1002)

| name | address |
| ---- | ------- |
| EntryPoint (Permissioned) | 0x87fe9653f640f6Fcf6cbd170701cDeEa74949F82 |
| KernelFactory | 0xAd810e77238c514B8873093F3247ae1c2B60405b |
| KernelImplementation | 0x51bE203f16b5342A856c5e9e7820f2a7c3CE95B4 |
| SimpleWeightedECDSAValidator | 0x4a2BAdE1d1efa849ae249720310d50229Be59772 |
| SCARegistry | 0x69AdF3A3AbfB56Cea28c7F01cCA66000228a11d5 |
| VerifyingPaymaster | 0xd94db1FE5A113b3467C2267f81485465Fd442ad6 |

## Deployed Services

### b2-zkevm-dev (1002)

| name | url |
| ---- | --- |
| AA Bundler | <http://43.157.191.32:14337> |
| Paymaster Signing Service | <http://43.157.191.32:14338> |
