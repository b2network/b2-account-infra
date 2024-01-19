# b2-account-infra

## Design

[https://github.com/b2network/b2-account-infra/issues/1](https://github.com/b2network/b2-account-infra/issues/1)

## Repositories

### Contracts

[aa-core](https://github.com/b2network/aa-core): forked from eth-infinitism/account-abstraction v0.6.0

[aa-account-kernel](https://github.com/b2network/aa-account-kernel): smart contract account forked from zerodevapp/kernel

[aa-deploy](https://github.com/b2network/aa-deploy): deployment scripts for AA related contracts using Foundry

### Bundler

[aa-bundler](https://github.com/b2network/aa-bundler): forked from etherspot/skandha

### SDKs / Packages

[aa-sdk](https://github.com/b2network/aa-sdk): AA SDK in Typescript, forked from zerodevapp/sdk

[aa-utils](https://github.com/b2network/aa-utils): AA utils in Typescript

[b2-account-agent](https://github.com/b2network/b2-account-agent): Account agent built upon AA SDK

[b2-go-aa-utils](https://github.com/b2network/b2-go-aa-utils): AA utils in Golang

### Wallets

[b2-aa-extension](https://github.com/b2network/b2-aa-extension): AA wallet proxy to access SCAs on B2 network

[b2-wallet-connector](https://github.com/b2network/b2-wallet-connector): wagmi connector and rainbow-kit integration

[b2-wallet-connector-web3-react](https://github.com/b2network/b2-wallet-connector-web3-react): web3-react connector

### Examples

[aa-demos](https://github.com/b2network/aa-demos): example to demonstrate aa-sdk usage

[wallet-proxy-rainbowkit-demo](https://github.com/b2network/wallet-proxy-rainbowkit-demo): example to integrate wallet proxy with wagmi hooks and rainbowkit

## Deployed Contracts

### b2-zkevm-testnet (1002)

| name | address |
| ---- | ------- |
| EntryPoint (Permissioned) | 0x4271A0C0e0621504A6614d1f94A49A5aa583aCd0 |
| KernelFactory | 0x188Ebf5e4353bBAb62fD92cbfD02D68C7A77c58C |
| KernelImplementation | 0x4f20B43473D97bACc081dCFbeECa8B6F9062D320 |
| SimpleWeightedECDSAValidator | 0xc5696A835527E8aEe673107Ce00AD740a4353a61 |
| SCARegistry | 0xc4433cbB8C1e0FE56bb49F4F8A0A639F902bB7Ca |
| VerifyingPaymaster | 0x394d3a8daB310209dB7ee916f01C8c5076181498 |

### b2-zkevm-testnet-haven (1102)

| name | address |
| ---- | ------- |
| EntryPoint (Permissioned) | 0x4271A0C0e0621504A6614d1f94A49A5aa583aCd0 |
| KernelFactory | 0x188Ebf5e4353bBAb62fD92cbfD02D68C7A77c58C |
| KernelImplementation | 0x4f20B43473D97bACc081dCFbeECa8B6F9062D320 |
| SimpleWeightedECDSAValidator | 0xc5696A835527E8aEe673107Ce00AD740a4353a61 |
| SCARegistry | 0xc4433cbB8C1e0FE56bb49F4F8A0A639F902bB7Ca |
| VerifyingPaymaster | 0x394d3a8daB310209dB7ee916f01C8c5076181498 |

## Public Services

### b2-zkevm-testnet (1002)

| name | url |
| ---- | --- |
| AA Bundler | <https://bundler-test.bsquared.network> |
| Paymaster Signing Service | <https://pm-test.bsquared.network> |
| AA Guard | <https://aa-guard-test.bsquared.network> |
| AA Registry | <https://aa-registry-test.bsquared.network> |

### b2-zkevm-testnet-haven (1102)

| name | url |
| ---- | --- |
| AA Bundler | <https://b2-aa-bundler-test.bsquared.network> |
| AA Guard | <https://b2-aa-guard-test.bsquared.network> |
| AA Registry | <https://b2-aa-registry-test.bsquared.network> |
