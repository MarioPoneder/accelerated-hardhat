![](https://user-images.githubusercontent.com/176499/96893278-ebc67580-1460-11eb-9530-d5df3a3d65d0.png) [![NPM Package](https://img.shields.io/npm/v/accelerated-hardhat.svg?style=flat-square)](https://www.npmjs.org/package/accelerated-hardhat) [![GitPOAP Badge](https://public-api.gitpoap.io/v1/repo/MarioPoneder/accelerated-hardhat/badge)](https://www.gitpoap.io/gh/MarioPoneder/accelerated-hardhat)

---

Hardhat is an Ethereum development environment for professionals. It facilitates performing frequent tasks, such as running tests, automatically checking code for mistakes or interacting with a smart contract. Check out the [plugin list](https://hardhat.org/plugins/) to use it with your existing tools.

Built by the [Nomic Foundation](https://nomic.foundation/) for the Ethereum community.

Join our [Hardhat Support Discord server](https://hardhat.org/discord) to stay up to date on new releases, plugins and tutorials.

## Accelerated Hardhat: Changes to original v2.12.4
This version comes with an accelerated hardhat network to allow for smoother interaction with MetaMask & DApps.

- Hardhat network (fork): avoid unnecessary JSON-RPC and keep account data (nonce, balance, code, storage) in memory
- Hardhat network (fork): introduced 'eth_call' data size limit of 10000 bytes (performance reasons)
- Hardhat network (fork): enable on-disk caching per default, but only store non-zero contract code ('eth_getCode')
- Hardhat network (fork): adapt account nonce in order to use MetaMask without an account reset on each new fork instance

(see commit history for details)

## Installation

To install Hardhat, go to an empty folder, initialize an `npm` project (i.e. `npm init`), and run

```
npm install --save-dev accelerated-hardhat
```

Once it's installed, just run this command and follow its instructions:

```
npx accelerated-hardhat
```

## Documentation

On [Hardhat's website](https://hardhat.org) you will find:

- [Guides to get started](https://hardhat.org/getting-started/)
- [Hardhat Network](https://hardhat.org/hardhat-network/)
- [Plugin list](https://hardhat.org/plugins/)

## Contributing

Contributions are always welcome! Feel free to open any issue or send a pull request.

Go to [CONTRIBUTING.md](./CONTRIBUTING.md) to learn about how to set up Hardhat's development environment.

## Feedback, help and news

[Hardhat Support Discord server](https://hardhat.org/discord): for questions and feedback.

[Follow Hardhat on Twitter.](https://twitter.com/HardhatHQ)

## Happy building!

👷‍♀️👷‍♂️👷‍♀️👷‍♂️👷‍♀️👷‍♂️👷‍♀️👷‍♂️👷‍♀️👷‍♂️👷‍♀️👷‍♂️👷‍♀️👷‍♂️
