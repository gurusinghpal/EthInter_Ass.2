# Function Frontend

This repository contains a simple Solidity smart contract and a basic frontend application that interacts with the contract and displays its values.

## Frontend Description

The frontend is a simple HTML and JavaScript application that allows you to interact with the `SimpleContract` and display its values.

### Prerequisites

To use this frontend, you'll need the following:

- An Ethereum provider (e.g., MetaMask)
- Contract address

### Getting Started

1. Clone this repository or copy the code for the smart contract and frontend files.

2. After cloning the github, you will want to do the following to get the code running on your computer:
   - Inside the project directory, in the terminal type: npm i
   - Open two additional terminals in your VS code
   - In the second terminal type: npx hardhat node
   - In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
   - Back in the first terminal, type npm run dev to launch the front-end.

  After this, the project will be running on your localhost. 
  Typically at http://localhost:3000/

3. Connect your Ethereum provider (e.g., MetaMask) to the network where your `Assessment` is deployed.

4. Interact with the contract using the provided form inputs and buttons in the frontend.

## Authors

Hetashi Guru Singh Pal 

[@gurusinghpal](https://www.linkedin.com/in/guru-singh-pal-99a305254/)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

