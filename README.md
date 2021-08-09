## Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![alt text](https://github.com/MrBearP/nervos-3/blob/master/ckb-call-sc.png)


2. The transaction hash from the console output (in text format).
```
0x4e23d0ef845d453a17bd2a14da698ceb83c45e335b607d5145d8229c78f3d933
```
3. The contract address that you called (in text format).
```
0x149028CBd8b3227b37AC5eF5f6810E7d3a893A65
```
4. The ABI for contract you made a call on (in text format).

```
abi = [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ];
  ```
