# restund

Restund is a modular and flexible STUN and TURN Server, with IPv4 and IPv6 support.

Already fix compile error in ubuntu 16.04 db.o error~~ 

## Features

Authentication module

Binding module

MySQL module

Statistics module

Status module

Syslog module

TURN module

## [Download](http://www.creytiv.com/pub)

Latest and previous releases of restund can be downloaded https://github.com/mrzeta/restund

## Building and installation

To build restund core and the modules we are using GNU Make. External dependencies are automatically detected by the makefile. 

libre

must be installed first.

To build restund with default options:

```
$ cd restund
$ make
$ sudo make install
```

A sample configuration file can be found in the etc directory of the restund package.