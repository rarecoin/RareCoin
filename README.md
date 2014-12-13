XDECoin v3 | Source Code
=======

This is A Community Takeover of XDoubleEagle.

Official Thread: https://bitcointalk.org/index.php?topic=841830

Website: http://xdecoin.org

Official Forum: http://doubleeagletalk.com
----------------------------------------------------------------------

MANDATORY UPDATE FIX.
You will need the Upated Source Link to Get pass Block 10001.
Update1 Link: https://github.com/XDEDev/XDECoin-UpdateFix

----------------------------------------------------------------------
Tor included - Compiling:

First you need to Update your Linux OS (Ubuntu)

1) sudo apt-get update

2) sudo apt-get upgrade

3) sudo apt-get install build-essential libssl-dev libboost-all-dev git libdb5.1++-dev libminiupnpc-dev screen

4) sudo apt-get install libevent-dev

-----------------------------------------------------------------------
Compilation Errors at End: libleveldb.a and libmemenv.a - Not Found! ! !

When Compiling xdecoind on Linux, if compilation get terminated at the end because of missing files:
libleveldb.a and libmemenv.a - Please use these commands to copy the Files from "src/leveldblinux directory.

1) cd XDECoin/src/leveldblinux

2) sudo cp libleveldb.a /XDECoin/src/leveldb

3) sudo cp libmemenv.a /XDECoin/src/leveldb

------------------------------------------------------------------------
