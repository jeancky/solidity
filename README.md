# The Solidity Contract-Oriented Programming Language
[![Join the chat at https://gitter.im/ethereum/solidity](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ethereum/solidity?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/ethereum/solidity.svg?branch=develop)](https://travis-ci.org/ethereum/solidity)

## Useful links
To get started you can find an introduction to the language in the [Solidity documentation](https://solidity.readthedocs.org). In the documentation, you can find [code examples](https://solidity.readthedocs.io/en/latest/solidity-by-example.html) as well as [a reference](https://solidity.readthedocs.io/en/latest/solidity-in-depth.html) of the syntax and details on how to write smart contracts.

You can start using [Solidity in your browser](http://remix.ethereum.org) with no need to download or compile anything.

The changelog for this project can be found [here](https://github.com/ethereum/solidity/blob/develop/Changelog.md).

Solidity is still under development. So please do not hesitate and open an [issue in GitHub](https://github.com/ethereum/solidity/issues) if you encounter anything strange.

## Building
See the [Solidity documentation](https://solidity.readthedocs.io/en/latest/installing-solidity.html#building-from-source) for build instructions.
```
Build for javascript
cd solidity
docker run -it -v $(pwd):/root/project -w /root/project trzeci/emscripten:sdk-tag-1.35.4-64bit
apt-get update
apt-get install wget gcc
apt-get install -y build-essential
./scripts/travis-emscripten/install_deps.sh
./scripts/travis-emscripten/build_emscripten.sh

bash tran.sh
```
## How to Contribute
Please see our [contribution guidelines](https://solidity.readthedocs.io/en/latest/contributing.html) in the Solidity documentation.

Any contributions are welcome!


