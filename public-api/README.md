![](https://img.shields.io/badge/status-wip-orange.svg?style=flat-square) Public APIs (core + http + cli)
=========================================================================================================

> This document presents the specifications for the IPFS APIs, namely: 'core', the programmatic interface, 'http', a networked API interface over HTTP and 'cli', the command line interface to interact with IPFS.

Authors:

- David Dias

Reviewers:

- Jeromy Johnson
- Juan Benet

# Abstract

This describes the [IPFS](https://ipfs.io/) APIs, including 'core', 'http' and 'cli'.

# Organization of this document

This RFC is organized by chapters described on the *Table of contents* section. Each of the chapters can be found in its own file.

## API

- [Core API (aka using IPFS as a package/module)](./core)
  - [JavaScript implementation details](https://github.com/ipfs/interface-js-ipfs-core)
  - [Golang implementation details](https://github.com/ipfs/interface-go-ipfs-core)
- [CLI (the ipfs daemon API)](./cli)
- [HTTP API](./http-api)
- [HTTP Gateway](./http-gateway)
