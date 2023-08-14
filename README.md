```markdown
# Simple Blockchain in Python

This repository contains a simple blockchain implementation in Python. The code is designed to be straightforward and easy to understand, making it an excellent starting point for learning about blockchain technology.

## How to Use

To use the code, follow these steps:

1. Clone this repository to your local machine:
   ```sh
   git clone <repository-url>
   ```

2. Open the `blockchain.py` file in a text editor.

3. Customize the blockchain by editing the code. You can adjust parameters such as the number of blocks to generate or the data stored in the blocks.

4. Once you've customized the code, run the blockchain by executing the following command in your terminal:

   ```sh
   python blockchain.py
   ```

   This will create a blockchain with the specified number of blocks and print the blockchain to the console.

## Code Explanation

The `blockchain.py` file defines the following classes and functions:

### Block Class

Represents a block in the blockchain. It has the following attributes:

- `index`: The index of the block in the blockchain.
- `previous_hash`: The hash of the previous block in the blockchain.
- `timestamp`: The timestamp of the block.
- `data`: The data of the block.
- `hash`: The hash of the block.

### `calculate_hash` Function

Calculates the hash of a block. The hash is a unique identifier for the block and is used to verify the block's integrity.

### `create_genesis_block` Function

Creates the genesis block, which is the first block in the blockchain. The genesis block has a previous hash of 0 and contains no data.

### `create_new_block` Function

Creates a new block in the blockchain. The new block takes the previous block as input and generates a new hash. The block also contains user-defined data.

### `main` Function

This function initializes the blockchain and adds blocks to it. The blockchain starts with the genesis block, and subsequent blocks are added one by one. Each new block contains the hash of the previous block, linking the blocks together in a chain.
