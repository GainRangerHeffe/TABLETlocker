# TABLET Locker and Disperser

A single-file web app for locking and sending tokens on PulseChain, made for the $TABLET (PulseChain Tablet) community. Everything, including markup, styles and script, is in `index.html`.

## Features

**Token locker**

- Lock any PRC20 token with a vesting period of 30 to 365 days
- Time-locked smart contract, up to 100 locks per wallet
- Pay the fee in PLS, by burning TABLET, or as a percentage of the locked tokens (1 to 50%)

**Token disperser**

- Send a token to up to 200 recipients in one transaction
- Same three fee options

## Use

Open `index.html` in a browser with a PulseChain wallet extension, or serve the folder:

```bash
npx serve .
```

Connect a wallet, pick Locker or Disperser, enter the token address and amounts, and confirm in the wallet.

## Notes

- The contracts are not audited. Check the contract addresses in `index.html` before sending funds.
- The social preview tags point at `pulsechaintablet.com`, which is not being renewed.
