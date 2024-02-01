# Candy Machine User Interface Configuration Guide

Welcome to the guide that will help you set up the user interface (UI) for your Candy Machine. This UI plays a crucial role in the NFT minting process, enabling users to use their Phantom wallets for transactions with your generated SPL token.

## Prerequisites

Before you start, make sure you have:

- A Candy Machine configured with necessary details in the `config.json` file (price, quantity, symbol, seller fee basis points, SPL token account, SPL token, go-live date, creator info).
- A Phantom wallet set up for minting purposes.
- A newly created SPL token.

## Configuration Steps

### Step 1: Setting Up the SPL Token

Follow the guidelines provided in Lesson Three to create an SPL token, if you haven't done so already. Remember to note down the SPL token's address.

### Step 2: Updating Candy Machine Configuration

Modify your Candy Machine's `config.json` file with the following updates:

- `splTokenAccount`: Update this with the address of your newly created SPL token account.
- `splToken`: Update this with the address of your SPL token.

### Step 3: Setting Up the User Interface

For instructions on creating a UI for your Candy Machine, refer to the "Quick Node: Set Up a Minting Site" tutorial. This UI will enable users to connect their Phantom wallets and mint NFTs using your SPL token.

### Step 4: Modifying Minting Logic

Alter the minting logic in your SPL project (as outlined in Lesson Three) to either mint NFTs directly to the user's Phantom wallet address or change the transfer function to send minted NFTs to your Phantom wallet.

### Step 5: Conducting Tests

Test your setup thoroughly by minting or transferring your SPL token to a Phantom account and using the UI to mint NFTs. Ensure that the process is smooth for users who pay with the SPL token.

---
