# ether-go

This library ws created because

1. you may not like signing via RPC or IPC calls
2. you may not want to use the key store which keeps wanting passwords etc. and only workds if a key is unlocked.


You will need to load the following...

```
go get github.com/ethereum/go-ethereum/common
go get github.com/ethereum/go-ethereum/core/types
go get github.com/ethereum/go-ethereum/crypto
```

NOTE: to run some of the examples You will need to have some ether in the banker account 
(run it on the test net then you can mine into it - get the address from getKeyAddress.go)

The tests are a bit dodgy but the functionality is there....

### mixed ether-go and JSON examples:


1. clientVersion.go   just JSON-RPC untidy 
2. bankerBalance.go

### ether-go examples

1. getKeyAddress.go						create or load a key and print address
2. firstContractPlayground.go	a load of calls here - have a look


