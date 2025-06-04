#BlockchainVotingApp
##E-Voting Web Application - Mini Project
A decentralized and transparent e-voting system built using Ethereum, Solidity, React, and Web3.js. 
This application enables secure voter registration, voting, and result management on the blockchain, ensuring tamper-proof elections.

Features
-Voter self-registration using Voter ID and password
-One vote per registered voter ensured by smart contract logic
-Admin dashboard to start/end elections and manage candidates
-Real-time vote count visibility after election ends
-All data stored on the Ethereum blockchain
-User-friendly frontend built with React
-Alerts and validation for common issues (e.g., duplicate voting)

Tech Stack
Smart Contract:	Solidity, Truffle
Frontend:	React.js, Tailwind CSS
Blockchain Interaction:	Web3.js
Local Blockchain (for development):	Ganache

Installation & Setup
Prerequisites
Node.js
Truffle
Ganache
MetaMask Extension

Clone the Repository
git clone https://github.com/neha-cj/BlockchainVotingApp.git
cd BlockchainVotingApp

1. Start Ganache
Open Ganache and make sure the RPC server is running on http://127.0.0.1:7545.

2. Compile and Migrate Contracts
truffle compile
truffle migrate --reset

4. Start React Frontend
npm install
npm start

 
Usage
-Voter Registration
  Voters register using their Voter ID and a password.
  Each Voter ID must be unique.
-Login
  Voters and Admin can log in through separate interfaces.
-Admin Functions
  Start and End the election.
  View total vote counts after election ends.
-Voting
  Voters can cast a single vote once the election has started.
  Results are revealed only after the election is ended by the admin
