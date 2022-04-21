
PROJECT: Decentralized Star Notary Service Project - For this project, you will create a DApp by adding functionality with your smart contract and deploy it on the public testnet.

ToDo

This Starter Code has already implemented the functionalities you implemented in the StarNotary (Version 2) exercise, and have comments in all the files you need to implement your tasks.

Dependencies

For this project, you will need to have:

Node and NPM installed - NPM is distributed with Node.js
# Check Node version
node -v
# Check NPM version
npm -v
Truffle v5.X.X - A development framework for Ethereum.
# Unsinstall any previous version
npm uninstall -g truffle
# Install
npm install -g truffle
# Specify a particular version
npm install -g truffle@5.0.2
# Verify the version
truffle version
Metamask: 5.3.1 - If you need to update Metamask just delete your Metamask extension and install it again.

Ganache - Make sure that your Ganache and Truffle configuration file have the same port.

Other mandatory packages:

cd app
# install packages
npm install --save  openzeppelin-solidity@2.3
npm install --save  truffle-hdwallet-provider@1.0.17
npm install webpack-dev-server -g
npm install web3
Run the application

Clean the frontend
cd app
# Remove the node_modules  
# remove packages
rm -rf node_modules
# clean cache
npm cache clean
rm package-lock.json
# initialize npm (you can accept defaults)
npm init
# install all modules listed as dependencies in package.json
npm install
Start Truffle by running
# For starting the development console
truffle develop
# truffle console

# For compiling the contract, inside the development console, run:
compile

# For migrating the contract to the locally running Ethereum network, inside the development console
migrate --reset

# For running unit tests the contract, inside the development console, run:
test
Frontend - Once you are ready to start your frontend, run the following from the app folder:
cd app
npm run dev
