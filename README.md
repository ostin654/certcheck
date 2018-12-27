# Certcheck

Check SSL certificate validity.

Usage:

`./certcheck <file.txt> <treshold>`

* file.txt - text file, each line domain:port
* treshold - days to expire

## Requirements

* timeout utility
* openssl
* perl Time::Piece

## Timeout on Mac

`brew install coreutils`
`cp /usr/local/opt/coreutils/libexec/gnubin/timeout /usr/local/bin/`
