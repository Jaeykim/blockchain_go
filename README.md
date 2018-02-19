# Blockchain in Go

A blockchain implementation in Go, as described in these articles:

1. [Basic Prototype](https://jeiwan.cc/posts/building-blockchain-in-go-part-1/)
2. [Proof-of-Work](https://jeiwan.cc/posts/building-blockchain-in-go-part-2/)
3. [Persistence and CLI](https://jeiwan.cc/posts/building-blockchain-in-go-part-3/)
4. [Transactions 1](https://jeiwan.cc/posts/building-blockchain-in-go-part-4/)
5. [Addresses](https://jeiwan.cc/posts/building-blockchain-in-go-part-5/)
6. [Transactions 2](https://jeiwan.cc/posts/building-blockchain-in-go-part-6/)
7. [Network](https://jeiwan.cc/posts/building-blockchain-in-go-part-7/)

# How to build

1. Set go environment like
```
export GOROOT=$HOME/bin/go
export GOPATH=$HOME/golang
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOBIN
```

2. go get packages
```
go get github.com/boltdb/bolt/...
go get golang.org/x/crypto/ripemd160
go build
```
