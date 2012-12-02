# SOCKS client library

Async SOCKS client library to connect to SOCKS4, SOCKS4a and SOCKS5 servers

## Description

TODO: Full description, simple introduction, what is SOCKS, how does it work, what does this library actually do.

## Example

TODO:
```PHP

// see example.php

```

### Using SSH as a SOCKS server

If you already have an SSH server set up, you can easily use it as a SOCKS tunnel end point. On your client, simply start your SSH client and use the `-D [port]` option to start a local SOCKS server (quoting the man page: a `local "dynamic" application-level port forwarding`) by issuing:

`$ ssh -D 9050 ssh-server`

### Using the TOR network to tunnel SOCKS connection

TODO: 

## Install

The recommended way to install this library is [through composer](http://getcomposer.org). [New to composer?](http://getcomposer.org/doc/00-intro.md)

TODO: not actually published on packagist yet.

```JSON
{
    "require": {
        "clue/Socks": "dev-master"
    }
}
```

## TODO

* Publish on packagist
* Automatically pick *best* SOCKS version available

## License

MIT, see license.txt
