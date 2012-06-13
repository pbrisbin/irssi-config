# Irssi

## Features

1. Minimalist theme
2. Freenode setup
3. Bitlbee setup
4. SASL Authentication
5. Active window list
6. Screen away
7. Highlight window

See `./scripts` for other useful scripts.

## Prerequisites

1. A bitlbee setup
2. Any perl libraries required by the scripts (including SASL auth)

## Install

~~~ 
$ cp ~/.irssi ~/irssi-backup
$ git clone https://github.com/pbrisbin/irssi-config ~/.irssi
$ cp ~/.irssi/sasl.auth.example ~/.irssi/sasl.auth
$ vim ~/.irssi/sasl.auth # add username/password for freenode
~~~

## Thanks

All the various script authors. There should be correct author and 
license info the script comments themselves; if not, let me know.
