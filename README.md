# Monad-curvance-bot-auto

Monad Curvance Bot is an automated bot designed for executing transactions with Curvance on the Monad Testnet network in compliance with standardized operational procedures.

Source: [Curvance on Monad](https://monad.curvance.com/monad)

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/jeje283u29/Monad-curvance-bot-auto.git
   cd Monad-curvance-bot-auto
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Prepare private keys:**

   - Create or edit `privateKeys.json` to include your Ethereum private keys as an array of strings. Each private key should be enclosed in double quotes.

   **Example `privateKeys.json` (correct format):**
   ```json
   [
       "private_key_1_here",
       "private_key_2_here"
   ]
   ```

   Ensure each private key string is correctly formatted as shown above.

## Usage

- **Run the application:**

  ```bash
  node index.js
  ```

- Follow the prompts to enter the number of transactions to send per private key.

Last updated: Mon Apr  7 08:26:11 UTC 2025

