# Brickblock DApp Prototype

DO NOT USE! The code in this repository is a preview intended for educational purposes only. 

These are the Solidity contracts implementing the Brickblock Proof-of-Asset scheme.

## Setup

First, install dependencies:

    npm install
    npm install -g truffle ethereumjs-testrpc

Then run the testrpc server, compile and migrate the contracts:

    testrpc &
    truffle compile && truffle migrate

Now you can run the tests:

    truffle test

NOTE: The testrpc needs to be restarted for every test run, since the accounts run out of funds.
