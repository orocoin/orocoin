OroCoin integration/staging tree
================================

http://www.orocoin.or

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 OroCoin Developers

What is OroCoin?
----------------

OroCoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 
OroCoin Specs:

Coin Algorithm Script: Scrypt (POW)

Coin Abbreviation : ORO

Maximum Coin Supply : 23,529,412

Block halving : 250000 blocks

Coin base maturity : 20 blocks

PoW block reward : 40 ORO

Coinbase maturity : 20 blocks

Target spacing : 5 minutes

Transaction confirmations : 5 blocks

RPC port : 10232

P2P port : 10231
 
For more information, as well as an immediately useable, binary version of the OroCoin client sofware, see http://www.orocoin.co.

License
-------

OroCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the OroCoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/orocoin/orocoin/tags) are created
regularly to indicate new official, stable release versions of OroCoin.

