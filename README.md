# KViper: Semantics of Viper in K

In this repository we present a formal semantics of [Viper](https://github.com/ethereum/viper).
For more details, refer to [wiki](https://github.com/kframework/viper-semantics/wiki).

## Running KViper

KViper can be used to compile Viper programs to EVM bytecodes.

First, build KViper:
```
$ ./build.sh
```

Then, run KViper:
```
$ ./kviper.sh <pgm>.v.py
```

For example,
```
$ ./kviper.sh tests/examples/token/ERC20.v.py
```
