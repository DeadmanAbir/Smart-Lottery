
# Smart-Lottery

Smart-Lottery is a DApp, which is created  by writing the contract in solidity and the cotract is backed by  <b>Chainlink VRF V2</b> and <b>Chainlink Automation</b>

## Features

- A user have to enter the Lottery by paying some test eth.
- The project is deployed on Sepolia Testnet so make sure you change you metamask account to sepolia testnet.
- Now after some conditions are met and after a certain interval of time (which is 5 min hardcoded by me), <b>Chainlink Keepers</b> will automaticlly call a function from contract to choose a winner.
- The picking the winner involves a generation on random number which is again done by <b>Chainlink</b>.

## Installation

To run Smart-Lottery, you need to have node js and metamask installed on your system. After cloning the repo follow the following commands:



To start the program, run the following command:

```bash
npm install
```

Sometimes it may gave error while installing all the dependencies, if you get one then run:
```bash
npm install --legacy-peer-deps
```

After this you will have the project fully installed on your system.
## Disclaimer

This project is not fully optimized as it is developed by me individually. You can always create a PR for better optimization. 
- <b>Connect with me -</b> [Click](https://abir-dutta-porfolio.netlify.app/)
