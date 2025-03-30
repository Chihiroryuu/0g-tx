# 0g Testnet auto tx

for auto swap 0g testnet

## Features

- Multi Account
- Support Proxy
- Swap USDT/ETH
- Swap ETH/USDT
- Swap USDT/BTC
- Swap BTC/USDT


## Installation

1. Clone the repository:

   ```sh
   https://github.com/Chihiroryuu/0g-tx.git
   cd 0g-tx
   ```

2. Instal Packages and build packages:

   ```sh
   npm install
   npm run build
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line) (Optional).

   ```
   http://user:pass@host:port
   http://user:pass@host:port
   http://user:pass@host:port
   ```

4. Create privatekey `nano privatekey.txt` and put your private key one per line

   ```
   0xprivatkey1
   0xprivatkey2
   0xprivatkey3
   0xprivatkey4
   ```

## Usage

1. Run the bot:

```sh
npm run start
```

