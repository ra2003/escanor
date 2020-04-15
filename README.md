![logo](https://raw.githubusercontent.com/mambisi/escanor/master/static/logo.png)

## Welcome to the Escanor

Escanor is a high performance in memory database written in [rust](http://rust-lang.org/) it offers performance similar to redis and implement the [redis protocol](https://redis.io/topics/protocol) with useful additions for json data manipulations. This is a side project with the vision of making it into a major project any contributors are welcome.

## Features

- High Performance

- Non Blocking Key-Value

- Asynchronous Server 

- Great support for Json Storage

- Support for Redis Clients and Libraries

- Client Cli included.

## [Download](https://github.com/mambisi/escanor/releases)
Download the latest release from the [release page](https://github.com/mambisi/escanor/releases), binaries are available for Windows, Mac and Linux.

## [Install](https://github.com/mambisi/escanor/wiki/Installation)
Installation instructions are available in the [wiki page](https://github.com/mambisi/escanor/wiki/Installation)

## [Commands](https://github.com/mambisi/escanor/wiki)
Supported commands:
``set``,``get``,``del``,``get``,``geoadd``,``geodel``,``georem``,``georadius``,``georadiusbymember``
 ,``geohash``,``geojson``,``jset``,``jget``,``jpath``,``jmerge``
 checkout the wiki page on how to use these commands
[WIKI PAGE](https://github.com/mambisi/escanor/wiki)

## Run

```shell script
git clone https://github.com/mambisi/escanor.git
```
```shell script
cd escanor
```
```shell script
cargo run --bin escanor-server
```
```shell script
cargo run --bin escanor-cli
```