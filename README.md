# TurtleCoin(TRTL)

## [ANN]
```
Name:          : TurtleCoin  
Algorithm      : [CryptoNote](http://cryptonote.org)
                 ASIC resistant, same algo as monero, aeon and bytecoin  
Time           : 30 second block time - made by and for miners.  
Econ           : Two decimal places like USD  
Supply Cap     : Plenty.  
Address Prefix : "TRTL".   
Currency Code  : "TRTL".  
```

## Make a Wallet
Download the binary tarball distribution from the [Release](https://github.com/turtlecoin/turtlecoin/releases) section of the repo and unpack it, or build from source. Then run

```bash
./simplewallet
```

Press `G` to generate new wallet.  
enter filename (default wallet.bin)  
enter password (no confirmation, so be careful)  
type `address` to get your wallet address.

## Start the Daemon
With wallet running, run
```bash
./Turtlecoind
```

## Mine
With wallet and daemon running, run

```bash
miner --address <address>
```

## Official Communications
- http://turtlecoin.lol/
- http://discord.turtlecoin.lol
- http://twitter.turtlecoin.lol

## Github Repositories
- http://github.turtlecoin.lol

## Contributing
If you want to start contributing, the best bet right now is to join our discord and discuss with the community there. Look for RockSteady, bebop, or michelangelo for guidence. Cowabunga!

### Helpers Needed
- PR Team
- Graphics Team
- Mining Pool Operators (compatible with monero/aeon/bytecoin mining tools and pools)
- Windows Dev to compile builds
- Apple Dev to compile build
- Packagers to package various distributions (ArchLinux, Ubuntu, RHEL/CentOS/Fedora, etc)
