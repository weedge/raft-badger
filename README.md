raft-badger
===========

This repository provides the `raftbadger` package. The package exports the
`BadgerStore` which is an implementation of both a `LogStore` and `StableStore`.

It is meant to be used as a backend for the `raft` [package here](https://github.com/hashicorp/raft).

This implementation uses [BadgerDB](https://github.com/dgraph-io/badger). BadgerDB is
a simple persistent key-value store written in pure Go. It has a Log-Structured-Merge (LSM) 
design and it's meant to be a performant alternative to non-Go based stores like 
[RocksDB](https://github.com/facebook/rocksdb).

Documentation
=============
The documentation for this package can be found on [Godoc](http://godoc.org/github.com/bbva/raft-badger) here.