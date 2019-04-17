# Hello World

This project contains code from following Amazingandyyy's tutorial at [Medium.com](https://medium.com/etherereum-salon/hello-ethereum-solan-contract-4643118a6119).

This project uses truffle testrpc to start a server to depoly the contracts and run the tests.

Navigate to the folder containing the *Hello World* project, and execute the following codes:

	npm install testrpc
    
To start the server, execute:

	testrpc

In another terminal, navigate to the project folder, compile the contracts and deploy them by executing the following:

	truffle compile
    truffle migrate --reset

This will deploy the contracts to localhost:8545. To run the test file, execute the following:

	truffle test ./test/hello_eth_salon.js

This will run the test script and output the results.
