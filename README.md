## Setup

```
npm install -g --save-dev truffle
npm install --save-dev dotenv @truffle/hdwallet-provider
npm install --save-dev truffle-plugin-verify
```

## Private key

Create .env file with a private key:

```
PKEYS="YOUR_PRIVATE_KEY"
```

## Deploy contract

```
truffle migrate --network testnet
```

## Verify contract

```
truffle run verify HocusPocus --network testnet --debug
```

Example output of verification:

```
...
Checking status of verification request 588dd5ea2bc6363e1cfefb504e57506234a5e62f6272f6c9
Pass - Verified: https://scan.v2b.testnet.pulsechain.com/0x588Dd5EA2Bc6363E1CFefb504e57506234a5E62f#code
Successfully verified 1 contract(s).
```
