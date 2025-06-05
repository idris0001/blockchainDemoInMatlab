# MATLAB Blockchain Demo

This repository contains a simple MATLAB implementation of a blockchain miner that demonstrates the fundamental concepts of blockchain technology:

- **Block Construction:** Creating blocks that include data, a nonce, and the hash of the previous block.
- **SHA-256 Hashing:** Using SHA-256 to generate secure cryptographic hashes of each block.
- **Proof-of-Work Mining:** Adjusting the nonce to meet a difficulty target (e.g., leading zeros in the hash).

## Features

- Educational example ideal for understanding blockchain mechanics.
- Illustrates how blocks link securely via the `previousHash` field.
- Easy-to-read MATLAB script with comments explaining each step.

## Getting Started

1. Open MATLAB.
2. Run the `blockchain_demo.m` script.
3. Observe how blocks are mined with hashes that meet the difficulty criteria.
4. Review the output hashes to see the chained structure.

## Example Output
Block t hash: 0000ac5100c4b3e2d3d895cd7b457ba7f336fa9bdae68b2e9f8bb14673f4e3bb
Block t+1 hash: 0000f19dd5d0b77a2f7b6caa766bf553404b7eef5913d525bf883e01408377ad
