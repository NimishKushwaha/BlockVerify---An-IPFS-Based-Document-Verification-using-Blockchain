# BlockChain-Based Document Verification with IPFS

This project aims to create a secure and decentralized system for document verification using Blockchain and InterPlanetary File System (IPFS) technologies. The system stores the hash of the documents in the Blockchain network and the documents themselves in the IPFS network. This ensures that the documents cannot be tampered with or altered, and they can be easily retrieved and verified by authorized parties.

## Features

- Secure document verification using Blockchain and IPFS technologies
- Decentralized system, with no central authority or single point of failure
- Fast and easy verification process, with no need for intermediaries or third-party services
- User-friendly interface for document upload and verification
- Support for multiple document types and formats

## Requirements

- Node.js and npm installed on your system
- MetaMask Wallet
- IPFS client (Currently not working due ipfs server error)

## Installation

1. Clone this repository: 
``https://github.com/DevAloshe/BlockChain-Based-Document-Verfication-With-IPFS.git``


2. Install the required packages:

``cd BlockChain-Based-Document-Verfication-With-IPFS
npm install``

3. Create a metamask account.
4. Add a MATIC polygon network.
5. Load MATIC from https://faucet.polygon.technology/
6. Open Remix IDE and deploy the smart contract (.sol file) after connecting metamask to the Remix's website.
7. Copy the smart contract address from the IDE and paste it into the code.
8. Open the application in your browser using Liver Server Extension.
9. Connect the website to the metamask.
10. Create another MATIC polygon network.
11. One account will make an another account as an admin.
12. Upload and verify the documents from the admin account.


## Usage

1. The owner of the system must first add an exporter to the list of authorized parties. This is done by clicking on the "Add Exporter" button and entering the exporter's Ethereum address.
2. Upload a document to the system by clicking on the "Upload Document" button and selecting a file from your computer. The document will be encrypted and stored in the IPFS network, and its hash will be recorded in the Blockchain.

3. Verify a document by clicking on the "Verify Document" button and entering its unique identifier (hash) in the input field. The system will retrieve the document from the IPFS network, decrypt it, and compare its hash with the one recorded in the Blockchain.

4. The system will display a message indicating whether the document is authentic or not.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Metamask documentation
- Solidity and Web3.js documentation
- IPFS documentation
- Truffle documentation

## Sample Output
1. Login
![login](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/62119a2c-95ac-4a03-ade8-5df8ca5c419f)

2. Homepage
![homepage1](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/6b450e79-39e0-4d38-9933-1b190be948f9)
![homepage2](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/2c848495-628f-47b3-8d23-84158f07198c)
   
3. Admin Exporter
![Screenshot (371)](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/c3bef3ac-0215-432a-82b2-9306b2f63146)

4. Upload a document
   ![Screenshot (368)](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/13b63fe2-b681-4d4f-a5fa-aa9910a3f5ea)
![Screenshot (369)](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/3dc0e9de-2a09-4c57-a8c5-bf0758574e3b)

5. Verify a document
   ![Screenshot (370)](https://github.com/NimishKushwaha/BlockVerify---An-IPFS-Based-Document-Verification-using-Blockchain/assets/128953212/5710d5c1-629c-41e5-af57-62c8e970b7ba)


## Contributors

- <img src="https://github.com/NimishKushwaha.png" width="25" height="25" style="border-radius: 5;"> Nimish Kushwaha ([NimishKushwaha](https://github.com/NimishKushwaha))
<!--- <img src="https://github.com/bikrant07.png" width="25" height="25" style="border-radius: 5;"> Ayush Kushwaha ([bikrant07](https://github.com/bikrant07))
- <img src="https://github.com/Gungunkhaitan.png" width="25" height="25" style="border-radius: 5;"> Aashutosh Kumar Pandit ([Gungunkhaitan](https://github.com/Gungunkhaitan)) -->


## Contact

For questions or inquiries, please reach out to the project maintainers at [kushwahanimish@gmail.com](mailto:kushwahanimish@gmail.com).

Credit: OrioChain


