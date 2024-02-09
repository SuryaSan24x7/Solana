# Solona
Solana Playground is browser based application that will let you write, build, and deploy on chain Solana programs. All from your browser. No installation needed.

It is a great developer resource for getting started with Solana development, especially on Windows.
![This is Solana Playground](1.png)
![SOLANA SCAN Blockchain DEVNET Transaction Details](2.png)
![Client code](3.png)
![Client interaction](4.png)
## How to run locally
Install tools
Instructions on how to install Solana can be found here.

https://docs.solanalabs.com/cli/Hinstall

Install dependencies
Extract the zip file in your project's directory and run:


yarn
Build

cd program
cargo build-sbf
Start a local test validator

solana-test-validator
Test

yarn test
Run client

yarn client

Note You might need to adjust the client and test code to fully work in local Node environment since there are playground exclusive features, e.g. if you are using pg.wallets.myWallet, you'll need to manually load each keypair.
