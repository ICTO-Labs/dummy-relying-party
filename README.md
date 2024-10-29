# Dummy Relying Party

This project is used in e2e tests for the BlockID project to test that a relying party can get the BlockID score for a user.

Verify your wallet at BlockID: https://blockid.cc
Live relying party: https://zetfo-paaaa-aaaap-qkmjq-cai.icp0.io

## Environment Variables

```
II_URL=https://identity.ic0.app
ISSUER_ORIGIN=https://blockid.cc
ISSUER_CANISTER_ID=znqos-ziaaa-aaaap-qkmia-cai
```


## Build

Instal dependencies and build:

```
npm ci
npm run build
```

## Deploy

Use dfx

```
dfx deploy
```
