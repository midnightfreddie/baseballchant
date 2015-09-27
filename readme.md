# Baseball Chant

Inspired by a rude GIF posted to https://www.reddit.com/r/TexasRangers/, I
decided to make a modifiable HTML or SVG version. HTML is good enough so far.

By default it performs (visually) [the "Let's go Rangers" chant](http://midnightfreddie.github.io/baseballchant/baseballchant.html). [This](http://midnightfreddie.github.io/baseballchant/baseballchant.html#?a=%23%25%24%21&b=THE&c=AN&d=GELS&bg=%23B71234) is closer to the GIF that inspired me. [This](http://midnightfreddie.github.io/baseballchant/baseballchant.html#?a=%23%25%24%21&b=THE&c=AS&d=TROS&bg=%23FF7F00) is more immediately relevant.


The settings can be changed and a URL built by adding the settings parameter: http://midnightfreddie.github.io/baseballchant/baseballchant.html#?settings

## Parameters

- a, b, c and d Are the three words / four syllables displayed (c and d are spaced as a single word displayed one part at a time)
- e is CLAP or whatever you wish it to be instead
- bg is a CSS color value ([this site](http://teamcolors.arc90.com/) has team color codes)
- beat is the half-beat time in milliseconds (default is 200, so each syllable is 0.4 seconds long)
- settings will show the settings and a link to reuse for those parameter settings

## Future Ideas

- Figure out how to take the logic out of the controller and put it in services or factories or whatever Agnulary things they should be in.
- Animate the words
