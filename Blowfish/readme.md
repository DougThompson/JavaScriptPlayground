# Blowfish Encryption #

A JavaScript implementation of [Bruce Schneier's Blowfish algorithm](http://www.schneier.com/blowfish.html) and [Wikipedia](http://en.wikipedia.org/wiki/Blowfish_(cipher)).  This uses CBC (cipher block chaining) to obscure repeated blocks, and it also allows for a random pre-fix pad to keep same text blocks from encrypting to the same value.

Even though Bruce Schneier recommends using TwoFish now, I still think this is useful and had some fun converting it from C# to JavaScript.