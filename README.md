# 🧾 Hello World Smart Contract

A simple smart contract written in Solidity that stores and returns a "Hello World" message.
This project is a beginner-friendly introduction to Ethereum smart contracts.

---

## 📌 Features

* Written in Solidity (^0.8.0)
* Demonstrates:

  * State variables
  * Public view functions
* Easy to deploy and test

---

## 🛠️ Technologies Used

* Solidity
* Ethereum Blockchain
* Truffle / Remix IDE

---

## 📂 Project Structure

```
FirstSmartContract/
│── contracts/
│   └── HelloWorld.sol
│── migrations/
│── test/
│── truffle-config.js
```

---

## 📜 Smart Contract Code

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloWorld {

    string private helloMessage = "Hello world";

    function getHelloMessage() public view returns (string memory) {
        return helloMessage;
    }
}
```

---

## 🚀 How to Run / Deploy

### 🔹 Using Remix (Easiest)

1. Go to https://remix.ethereum.org
2. Create a new file `HelloWorld.sol`
3. Paste the contract code
4. Compile the contract
5. Deploy using "Deploy & Run" tab
6. Call `getHelloMessage()`

---

### 🔹 Using Truffle

Install Truffle:

```
npm install -g truffle
```

Compile contract:

```
truffle compile
```

Deploy contract:

```
truffle migrate
```

---

## 📖 What You Learn

* Basics of Solidity syntax
* How smart contracts store data
* How to interact with contract functions

---

## 🔐 Future Improvements

* Add setter function to update message
* Integrate with frontend (React / Web3.js)
* Deploy on testnet (Sepolia / Goerli)

* Your Name

---

## 📄 License

This project is licensed under the MIT License.
