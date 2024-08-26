# Blockchain
Simple blockchain using python

## License
This project is licensed under the terms of the GNU General Public License (GPL). See the LICENSE file for more information.

## Project Overview
This is a basic implementation of a blockchain in python. The blockchain is designed to be simple and easy to understand, while still maintaining the core principles of a blockchain.

## Features
* A simple blockchain data structure
* Ability to add new blocks to the chain
* Ability to register new nodes
* Ability to resolve conflicts using a consensus algorithm

## API Endpoints
* `/chain`: Returns the entire blockchain
* `/transactions/new`: Creates a new transaction
* `/nodes/register`: Registers a new node
* `/nodes/resolve`: Resolves conflicts using a consensus algorithm

## Requirements
* Python 3.x
* Flask
* hashlib
* urlparse
* requests

## Installing Requirements
To install the required dependencies, run the following command:
```bash
pip install Flask hashlib urlparse requests
```
## Running the Project
To run the project, simply execute the `blockchain.py` file. The blockchain will be available at `http://localhost:5000`.

## Contributing
Pull requests are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.