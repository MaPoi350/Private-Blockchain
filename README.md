# Private Blockchain Application

This is the application of a private Blockchain, which can create a Genesis Block, sign and verify a message, add a star structure and look up data linked to an address. 

## Getting started
- Install a bitcoin (test) wallet to generate a wallet address. Bitcoin Core is used here.
- Visual Studio Code is used as integrated development environment (IDE).
- The GET and POST API endpoints were implemented with Postman#
- Project dependancies to be installed by: `npm install`
- Application started with: `node app.js`


## API endpoints

- The application runs locally by default on the 8000 port.
- Following endpoints are used:
    - Generate the Genesis Block: (GET) `http://localhost:8000/block/height/0 `
    - Validate and sign the message: (POST) `http://localhost:8000/requestValidation`
    - Add a star and its data:(POST) `http://localhost:8000/submitstar`
    - Retrieve all stars linked to a wallet address: (GET) `http://localhost:8000/blocks/$walletaddress$`


## Example

![Example](https://user-images.githubusercontent.com/94952069/151721590-6bdfaaa0-3f3d-41cb-b579-5f6fcf8afc6c.PNG)
