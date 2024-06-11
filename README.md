

# NFT Minting and Management System

This JavaScript project provides a simple system to mint and manage Non-Fungible Tokens (NFTs). It includes functions to create NFTs, list all created NFTs, and get the total supply of minted NFTs.

## Features

- Mint NFTs with metadata such as name, creator, image URL, price, and creation year.
- List all minted NFTs and view their metadata.
- Get the total supply of minted NFTs.

## Installation

To run this project locally, you'll need Node.js installed on your machine. Once Node.js is set up, you can clone this repository and run the project.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nft-minting-management.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nft-minting-management
   ```

## Usage

After cloning the repository, you can run the JavaScript code to mint NFTs and manage them.

```javascript
// NFT Minting Function
function mintNFT(name, creator, imageURL, price, creation_year) {
    const nft = {
        "name": name,
        "creator": creator,
        "imageURL": imageURL,
        "price": price,
        "creation_year": creation_year
    };
    nfts.push(nft);
}

// Function to list all NFTs
function listNFTs() {
    for(let i = 0; i < nfts.length; i++) {
        console.log("\nName: " + nfts[i].name);
        console.log("Creator: " + nfts[i].creator);
        console.log("Image URL: " + nfts[i].imageURL);
        console.log("Price: " + nfts[i].price);
        console.log("Creation Year: " + nfts[i].creation_year);
    }
}

// Function to get total supply of NFTs
function getTotalSupply() {
    console.log("\nTotal Supply: " + nfts.length);
}

// Array to hold NFTs
let nfts = [];

// Mint some NFTs
mintNFT("Sunset Overdrive", "Nikhil Chib", "https://example.com/sunset.jpg", 50000, 2021);
mintNFT("Mountain View", "Ridhima Rajput", "https://example.com/mountain.jpg", 75000, 2020);
mintNFT("City Lights", "Joelin J Jacob", "https://example.com/city.jpg", 10000000, 2019);
mintNFT("Ocean Breeze", "DivyaPrakash", "https://example.com/ocean.jpg", 800000, 2022);
mintNFT("Forest Whisper", "Eklavya Sharma", "https://example.com/forest.jpg", 65000, 2018);

// List all NFTs
listNFTs();

// Print total supply of NFTs
getTotalSupply();
```

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
