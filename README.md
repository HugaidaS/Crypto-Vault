# myVault 60/40 Crypto Strategy Vault

add credentials.js - alchemy key, private key,address,etherscan api key
code credentials.js (Enter Kovan wallet address with funds and Alchemy/Etherscan API Keys)
npm install
npx hardhat compile
npx hardhat node --fork https://eth-kovan.alchemyapi.io/v2/YourAlchemyAPIKeyHere
npx hardhat test --network local
npx hardhat run scripts/deploy.js --network kovan
