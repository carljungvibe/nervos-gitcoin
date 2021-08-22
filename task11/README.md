# TASK11 - Modify The Ported DApp So It Supports Ethereum Assets Via Force Bridge
### 1-) A screenshot of the accounts you created

<img src="https://github.com/carljungvibe/nervos-gitcoin/blob/master/task11/acc-list.png" />


### 2-) A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqrww4kj7tn4whe920yvgl7fvg4jrq6weqqrrs6nr" > Explorer link </a>

### 3-) A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/carljungvibe/nervos-gitcoin/blob/master/task11/deposit.png" />

### 4-) A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/carljungvibe/nervos-gitcoin/blob/master/task11/call.png" />

### 5) The transaction hash of the "Contract call" from the console output

```bash
0xaa02b550b3f126e449f0273bb906810ebab1ba7383112abfee203f3ebb805350
```
### 6) The contract address that you called

```bash
0x8C16d0FbC8b93aDeBab83E1528909efB761A733c
```

### 7) The ABI for contract you made a call on

```javascript
[
  {
    "inputs": [],
    "stateMutability": "nonpayable",
    "type": "constructor"
  },
  {
    "anonymous": false,
    "inputs": [
      {
        "indexed": false,
        "internalType": "uint256",
        "name": "id",
        "type": "uint256"
      },
      {
        "indexed": false,
        "internalType": "string",
        "name": "hash",
        "type": "string"
      },
      {
        "indexed": false,
        "internalType": "string",
        "name": "description",
        "type": "string"
      },
      {
        "indexed": false,
        "internalType": "uint256",
        "name": "tipAmount",
        "type": "uint256"
      },
      {
        "indexed": false,
        "internalType": "address payable",
        "name": "author",
        "type": "address"
      }
    ],
    "name": "ImageCreated",
    "type": "event"
  },
  {
    "anonymous": false,
    "inputs": [
      {
        "indexed": false,
        "internalType": "uint256",
        "name": "id",
        "type": "uint256"
      },
      {
        "indexed": false,
        "internalType": "string",
        "name": "hash",
        "type": "string"
      },
      {
        "indexed": false,
        "internalType": "string",
        "name": "description",
        "type": "string"
      },
      {
        "indexed": false,
        "internalType": "uint256",
        "name": "tipAmount",
        "type": "uint256"
      },
      {
        "indexed": false,
        "internalType": "address payable",
        "name": "author",
        "type": "address"
      }
    ],
    "name": "ImageTipped",
    "type": "event"
  },
  {
    "inputs": [],
    "name": "imageCount",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "",
        "type": "uint256"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "",
        "type": "uint256"
      }
    ],
    "name": "images",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "id",
        "type": "uint256"
      },
      {
        "internalType": "string",
        "name": "hash",
        "type": "string"
      },
      {
        "internalType": "string",
        "name": "description",
        "type": "string"
      },
      {
        "internalType": "uint256",
        "name": "tipAmount",
        "type": "uint256"
      },
      {
        "internalType": "address payable",
        "name": "author",
        "type": "address"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [],
    "name": "name",
    "outputs": [
      {
        "internalType": "string",
        "name": "",
        "type": "string"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "imgId",
        "type": "uint256"
      }
    ],
    "name": "getImage",
    "outputs": [
      {
        "components": [
          {
            "internalType": "uint256",
            "name": "id",
            "type": "uint256"
          },
          {
            "internalType": "string",
            "name": "hash",
            "type": "string"
          },
          {
            "internalType": "string",
            "name": "description",
            "type": "string"
          },
          {
            "internalType": "uint256",
            "name": "tipAmount",
            "type": "uint256"
          },
          {
            "internalType": "address payable",
            "name": "author",
            "type": "address"
          }
        ],
        "internalType": "struct Instagram.Image",
        "name": "",
        "type": "tuple"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "string",
        "name": "_imgHash",
        "type": "string"
      },
      {
        "internalType": "string",
        "name": "_description",
        "type": "string"
      }
    ],
    "name": "uploadImage",
    "outputs": [],
    "stateMutability": "nonpayable",
    "type": "function"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "_id",
        "type": "uint256"
      }
    ],
    "name": "tipImageOwner",
    "outputs": [],
    "stateMutability": "payable",
    "type": "function"
  }
]
```

### 8) Your Tron address

```bash
TGEDvMJMeTo7TnujhFtT81gZG1mKs8ZUU8
```

















