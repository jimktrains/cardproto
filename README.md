Card Game Protocol
------------------

I find it awkward that there is no standard way to write the rules for
common playing card games.  While I realize that not all games could be
accommodated by a fixed protocol (and associated rules), I none-the-less
would like to attempt to fit as many into it as possible.

Essentially, I envision an agreed-upon set of actions (the protocol) and
hooks run for each event.  The hooks could be made in any language, but
I envision "game files" with Lua code in them to help standardize the
game play.

I envision using shuffling techniques like mental poker for shuffling
cards securely, _i.e._ no player can know a card not dealt to them or in
the discard. The hooks being responsible for honest play, just as other
players need to ensure that that a player in real life isn't cheating.
