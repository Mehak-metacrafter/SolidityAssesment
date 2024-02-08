# MyToken - Simple Ethereum Token Contract

Simple overview of use/purpose.

## Description

MyToken is a basic Ethereum token contract written in Solidity. It provides functionality for minting and burning tokens, along with storing essential token details such as name, abbreviation, and total supply.
## Getting Started

### Installing

You can obtain the MyToken contract by either copying the provided Solidity code or downloading it from the repository.

### Executing program

To deploy and interact with the contract, follow these steps:

1.Compile the Solidity code using a Solidity compiler such as Remix IDE or Truffle.

2.Deploy the compiled contract to an Ethereum network (e.g., Remix IDE, Truffle, or a custom deployment script).

3.Use web3.js, ethers.js, or any Ethereum client library to interact with the deployed contract.
```
// mint function
    function mint(address _address, uint _value) public
   {
      totalSupply += _value;
      balances[_address]+=_value;
    }
```



## Authors

[Mehak Thakur] [mehakthakur051003@gmail.com]




## License

This project is licensed under the MIT License - see the LICENSE.md file for details
