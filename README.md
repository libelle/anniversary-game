# Tenth Anniversary Game
So, for our tenth anniversary, I thought I'd make something slightly more ... _dynamic_ ... than
your standard Hallmark card. I thought a simple JavaScript game might be fun.
## Unicorns and Rainbows
Since everyone knows that a happy marriage is made of unicorns and rainbows, I figured I'd work with that. I didn't
reflect on the fact that writing even a simple game in JavaScript is like going through a divorce. In any case,
I decided to use animated GIFs as sprites, and do the rest in Canvas.

Note: This released version has a placeholder wedding picture (ring.jpg). Replace this with an appropriate image!

## Lessons Learned
1. It might be faster to write a game from scratch, but seriously, take the time to learn a framework and use it. With any luck, it will handle all those weird edge cases, and probably have better support for odd platforms.
1. Sound in JavaScript is nasty, and not very portable. Again, use a framework (or commit to modern browsers, and use Web Audio API).
1. Responsive design is all good, but for a game, it might make sense to commit to a fixed size for playability.
1. Users will resize the window in the middle of a game. Code should probably trap for that, and do the right thing.
1. Under iOS, things don't work quite as you'd expect. This game should have been optimized, and used something like the `touchAction` style to improve playability.
1. I expected players to launch a single rainbow at a time. In fact, there was a whole lot more clicking than that.

## License
This game, and all of the assets I have created are released under the MIT License. The sound files are either conversions or derivative works of the files from http://www.orangefreesounds.com which appear to be released into the public domain by the author. See the credits.html page for more information as to sources, and to help you determine if you may reuse the assets in your legal environment.