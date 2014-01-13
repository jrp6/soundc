soundc
======

Echo download URL for each human-readable soundcloud URL specified. Based on lukapusic / soundcloud-dl.

Why?
----

The Soundcloud website requires flash, and the other Soundcloud clients too are bloated. This script is as simple as a Soundcloud client can be: it just tells where the sound file can be found. Use command substitution and your favourite internet-capable music player.

Exit codes
==========
* 1: No argument
* 2: No songs found
* 3: Neither curl nor wget is installed