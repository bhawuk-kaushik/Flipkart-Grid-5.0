# Flipkart-Grid-5.0
#Team - TheDarKnights

Blockchain-based: Loyalty and Rewards Program using Fungible Tokens
The aim of the project is to create a comprehensive and user-friendly blockchain-based platform that utilizes fungible tokens to revolutionize the way users engage with purchasing items and coupons, while also enabling seamless token transfers among themselves. This aims to create a more user-centric, transparent, and innovative ecosystem that transforms the way users engage with digital assets and interact within the platform.

REQUIREMENTS:

STEP1 - Clone the repository in your device using git clone or you can simply download the code file from this github repository.

STEP2 - Open the code files in your own Virtual Environment or you can also use VSCode as the IDE for an inbuilt virtual enviroment to run your code files.

STEP3 - First go to the Smart Contract_Hardhat file and deploy the smart contracts. You will have to install node_module package npm init  and provide your Metamask Private Key in the env file. Next, you will have to deploy the smart contract npm hardhat deploy --networks sepolia.

STEP4 - Now after deploying the smart contracts you will have provide the smart contract address and its abi into the fabside_WebUI/pages/ethereum folder.

STEP5 - Now you need to install the following packages.

Ethers
npm install ethers
Tailwindcss
npm install -D tailwindcss
Dotenv
npm install dotenv
@openzeppelin
npm i @openzeppelin/contracts
alchemy-sdk
npm i alchemy-sdk
ipfs-http-client
npm i ipfs-http-client
jsonwebtoken
npm i jsonwebtoken
mongoose
npm i mongoose
react
npm i react
react-toastify
npm i react-toastify
