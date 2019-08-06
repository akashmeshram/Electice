# Electice
A decentralize voting platform using block chain technology

# Idea
We wish to develope a decentralized online voting system implemented as a smart contract on the Ethereum blockchain. 
This online application will be equipped with recent state-of-art cryptography techniques. This will provide transparency, integrity and confidentiality for a dependable and well grounded platform.

Main security requirements which we aim to meet are following:-
1) Fairness - Voting process is as per the Election commision protrocol.
2) Eligibility - Only authorized voters can submit their cast votes.
3) Privacy - All votes must be encrypt and should not reveal voting preferences of the voters.
4) Verifiability -  Only verified votes are counted to calculate the result.
5) End-to-End Voter Verifiable - Every voter is able to verify whether his/her vote is posted and counted correctly.

# Working of App
- The administrator will deploy a voting contract by confirming public parameters (such as the voting potrocol). 
- Each voter can then submit a vote via the voting contract, with each vote constituting a transaction of the blockchain system. 
- In case of the vote not being verified as valid by the checks performed in the smart contract, the transaction reverts. 
- After being mined by the blockchain’s consensus algorithm, the vote is considered final.

# Technologies to use
 1) Microsoft Azure Blockchain 
 2) Ethereum

# Use

1. Run the development console.
    ```javascript
    truffle develop
    ```

2. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

3. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
