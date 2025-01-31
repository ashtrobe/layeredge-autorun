# Layer Edge Auto Bot

- website : https://dashboard.layeredge.io/

## Features

- **Auto Run Node**
- **Support Proxy usage**
- **Auto Claim Points every hour**

## Prerequisites

- Node.js installed on your machine


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ashtrobe/layeredge-autorun.git
    cd layeredge-autorun
    ```

2. Install the required dependencies:
    ```sh
    npm install
    ```
3. paste proxy in `proxy.txt`:
-  format `http://username:password@ip:port` or `socks5://username:password@ip:port`
    ```sh
    nano proxy.txt
    ```
4. Fill Data 
    ```sh
    nano wallets.json
    ```
4. Run the script:
    ```sh
    npm run start
    ```


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).
