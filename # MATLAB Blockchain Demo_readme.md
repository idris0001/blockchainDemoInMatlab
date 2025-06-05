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

