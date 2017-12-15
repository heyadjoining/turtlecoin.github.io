---
layout: page
title: Docs
tagline:
excerpt: >
  TurtleCoin [TRTL] is a CryptoNote based blockchain focused on community, users, and fun
permalink: /docs.html
header:
  image: /assets/img/home-header.png
ref: about
lang: en
order: 1
---

## ANN
```
Name:          : TurtleCoin  
Algorithm      : [CryptoNote](http://cryptonote.org)
                 -ASIC resistant
                 -Enhanced Privacy
                 -Elastic Blocks
                 -Fair Mining
Time           : 30 second targey block time - made by and for miners.  
Econ           : Two decimal places like USD  
Supply Cap     : Plenty.  
Address Prefix : "TRTL".   
Currency Code  : "TRTL".  
```

## Installation

### Linux

Download the binary tarball distribution from the [Release](https://github.com/turtlecoin/turtlecoin/releases) page and unpack it, or build from source.

### Windows
### Mac

## Running TurtleCoin

### Starting the TurtleCoind Daemon
With _simplewallet_ running (in background or another terminal), run
```bash
./TurtleCoind
```
### Running the simplewallet Client

#### Linux

```bash
./simplewallet
```

#### Windows
#### Mac

### Create a Wallet
In the running `simplewallet` client:  
Press `G` to generate new wallet.  
Enter a filename for your wallet (default is _wallet.bin_).  
Enter a passphrase for your wallet. *Warning:* There is no passphrase confirmation, so be careful!

### Get Your Address
In the running _simplewallet_ client, type `address` and press enter.


## Using the TurtleCoin simplewallet

### Check Your Balance
In the running _simplewallet_, type `balance` and press enter to see your balance.

### Send TurtleCoin
In the running _simplewallet_, type
```
transfer 0 <destination_address> <amount>
```
(note that `0` is the _mixin_ arg. For enhanced security/privacy of the the transaction, increase this number)

## Mining

### Linux
With _simplewallet_ and `TurtleCoind` running (in background or another terminal), run

```bash
./miner --address <address>
```

## Official Communications
- <http://turtlecoin.lol/>
- <http://discord.turtlecoin.lol>
- <http://twitter.turtlecoin.lol>

## Github Repositories
- <http://github.turtlecoin.lol>

## Contributing
If you want to start contributing, the best bet right now is to join our discord and discuss with the community there. Look for RockSteady, bebop, or michelangelo for guidence. Cowabunga!
