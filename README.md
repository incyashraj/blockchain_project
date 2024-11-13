# Blockchain Project

This project is an independent blockchain infrastructure designed to run locally, enabling fundamental blockchain operations such as mining, validation, and chain inspection. 
Built with Python, Flask, and Postman for API testing, this setup lays the foundation for creating a custom cryptocurrency and integrating with tools like MetaMask and Remit for smart contracts.

## Features
- **Blockchain Operations**: Mine new blocks, validate the chain, and fetch chain details.
- **Proof of Work**: Implements a simple Proof of Work algorithm.
- **HTTP API**: Uses Flask to expose endpoints for blockchain interactions.
- **Extendable Architecture**: Can be extended to include cryptocurrency and smart contract functionality.

## Requirements

To run this project, you'll need the following:
- Python 3.10 or later
- Flask (for the HTTP API)

Install the required packages using:
```bash
pip install -r requirements.txt
```

## Setup and Running the Project
Clone the repository:

```bash
git clone https://github.com/incyashraj/blockchain_project.git
cd blockchain_project
```
## Install the dependencies:

```bash
pip install -r requirements.txt
```

Start the Flask server:

```bash
python blockchain.py
```
The server will run on http://127.0.0.1:8081.

## API Endpoints
Use the following endpoints to interact with the blockchain. These can be tested with tools like Postman.

Mine Block

URL: /mine_block
Method: GET
Description: Mines a new block using Proof of Work and adds it to the chain.
Response: Details of the newly mined block.

Get Chain

URL: /get_chain
Method: GET
Description: Fetches the current blockchain.
Response: The full chain and its length.

Check Validity

URL: /is_valid
Method: GET
Description: Checks if the current chain is valid.
Response: Validity status of the blockchain.

## Extending the Project

Cryptocurrency Creation

This project can be extended by implementing functionality to create a custom cryptocurrency. Key steps include:

Defining a coin structure and transactions.
Integrating wallets and transaction signing.
Implementing tools like MetaMask and Remit for handling smart contracts and cryptocurrency transactions.


MetaMask & Remit Integration

MetaMask: Allows users to interact with decentralized applications and manage tokens.
Remit: Enables integration with smart contracts to handle the cryptocurrency created.


## File Structure

blockchain.py: The main application file containing the blockchain and Flask API setup.
requirements.txt: Lists all dependencies required to run the project.

## Requirements.txt
This file lists the libraries required for the project. Run the following command to install them:

```bash
pip install -r requirements.txt
```
## License
This project is licensed under the MIT License.

## Contributors

Yashraj Pardeshi (@incyashraj) - Initial creator and developer of the project.


