# Numoen

<p align="center">
  <img src="./image/Numoen_logo2.png" width="200" alt="Numoen">
</p>

### An options marketplace for any ERC-20.

Smart contracts suite of Numoen, an automated market maker that lends out its LP shares to replicate "Squeeth," a call option-like derivative for any ERC-20. 

## Installation


```bash
forge install numoen/pmmp
```

## Local development

This project uses [Foundry](https://github.com/foundry-rs/foundry) as the development framework.

### Dependencies

```bash
forge install
```

```bash
npm install @openzeppelin/contracts
```

```bash
npm install create3-factory
```

### Compilation

```bash
forge build
```

### Test

```bash
forge test
```

### Local setup

In order to test third party integrations such as interfaces, it is possible to set up a forked mainnet with several positions open

```bash
sh anvil.sh
```

then, in a separate terminal,

```bash
sh setup.sh
```
