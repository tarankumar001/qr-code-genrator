# QR Code Generator with Node.js

This is a simple command-line QR code generator built using **Node.js**. The user inputs a URL, which is then converted into a QR code image and saved to a file. Additionally, the entered URL is saved in a `.txt` file for reference.

## Features
1. **User Input via CLI**: Prompts the user to enter a URL using the **Inquirer** package.
2. **QR Code Generation**: Generates a QR code for the URL using the **qr-image** package.
3. **Save URL**: Saves the entered URL to a `.txt` file using Node.js's **fs** (file system) module.

## Technologies Used
- [Node.js](https://nodejs.org/)
- [Inquirer](https://www.npmjs.com/package/inquirer) for command-line prompts.
- [QR-Image](https://www.npmjs.com/package/qr-image) for QR code generation.
- Native Node.js **fs** module for file operations.

## Prerequisites

To run this project locally, ensure you have the following installed:

- Node.js (v12.x or later)
- NPM (Node Package Manager)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/qr-code-generator.git
   cd qr-code-generator
