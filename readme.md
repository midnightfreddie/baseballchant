# Baseball Chant

Inspired by a rude GIF posted to https://www.reddit.com/r/TexasRangers/, I
decided to make a modifiable HTML or SVG version.

By default it performs (visually) the "Let's go Rangers" chant: http://midnightfreddie.github.io/baseballchant/baseballchant.html

This is closer to the GIF that inspired me:
http://midnightfreddie.github.io/baseballchant/baseballchant.html#?a=%23%25%24%21&b=THE&c=AN&d=GELS&bg=%23B71234

This is more immediately relevant:
http://midnightfreddie.github.io/baseballchant/baseballchant.html#?a=%23%25%24%21&b=THE&c=AS&d=TROS&bg=%23FF7F00

## Parameters

- a, b, c and d Are the three words / four syllables displayed (c and d are spaced as a single word displayed one part at a time)
- bg is a CSS color value ([this site](http://teamcolors.arc90.com/) has team color codes)
- beat is the half-beat time in milliseconds (default is 200, so each syllable is 0.4 seconds long)

## Future Ideas

- Make it easier to change the parameters.
- Auto size the text to be as big as possible without wrapping the "CLAP CLAP CLAP" line.
- Figure out how to take the logic out of the controller and put it in services or factories or whatever Agnulary things they should be in.
