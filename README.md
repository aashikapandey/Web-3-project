# VotingRewards

This project is a simple Solidity-based voting system that allows participants to vote for predefined candidates and earn reward tokens for their participation. The contract ensures that each voter can vote only once, and their vote is recorded securely on the blockchain.

## Features
- Predefined candidates: Alice, Bob, and Charlie.
- Voters can cast their vote only once.
- Each voter receives a reward of 10 tokens upon voting.
- Transparent vote counting.
- Smart contract deployed on the Edu Chain.

## Deployed Address
**Edu Chain Deployment Address:** 0x2E82a14E6fcFF8047AB1509531581444De4E2b0C

## Usage
1. Call the `vote(candidateIndex)` function with the index of your chosen candidate.
2. Check vote counts using `getVotes(candidateName)`.
3. View rewards using the `rewards` mapping.

## License
This project is open-source and available under the MIT License.

