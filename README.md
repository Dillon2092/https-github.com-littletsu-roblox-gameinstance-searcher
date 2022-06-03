# roblox-gameinstance-searcher
Simple node.js program that can tell you (in small games, see [limit](#limit) section) the game instance of a player in a place.
Simple node.js program that can tell you (in small games, see [limit](#limit) section) the game instance of a player in a place and has been tested to find game instances on games with around 1k players.

# How does it work
It gets the thumbnail of the requested user, goes through the game instances of the requested place, and compares the thumbnails of the user until one is matched.
