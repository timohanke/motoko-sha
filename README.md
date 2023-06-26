*DEPRECATED in favor of https://mops.one/sha2 / https://github.com/research-ag/sha2 which has much better performance.*

## The SHA Package

[![Build Status](https://github.com/enzoh/motoko-sha/workflows/build/badge.svg)](https://github.com/enzoh/motoko-sha/actions?query=workflow%3Abuild)

This package implements secure hash algorithms for the Motoko programming language.

### Usage

Calculate a SHA256 hash.
```motoko
public func sha256(data : [Nat8]) : [Nat8]
```
