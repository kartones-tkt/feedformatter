# Summary #

feedformatter is a Python library for generating news feeds in RSS and Atom formats.

# Description #

feedformatter is intended to be in many ways an "opposite" to the well-known and well-loved Python module [feedparser](http://www.feedparser.org/).  Whereas feedparser tries to turn any news feed in any format into a friendly data structure of lists and dictionaries, feedformatter tries to turn a friendly data structure of lists and dictionaries into a well-formatted news feed of whatever kind you like.

The ideal is that you should be able to parse some feed in the wild with feedparser, give the result to feedformatter to produce a new feed in the same format as the original, give _that_ feed to feedparser and get back exactly the same data structure as you got by giving feedparser the original.  At the moment feedformatter certainly falls short of that ideal, but it works well enough for simple tasks.  RSS 1.0, RSS 2.0 and Atom 1.0 are all supported.

# Instructions #

The [Tutorial](http://code.google.com/p/feedformatter/wiki/Tutorial) Wiki page contains a brief walk-through that should be enough to get you started.  For now, if you want to know anything else you'll have to either read the code or ask me nicely.

# The future #

I wrote feedformatter because I needed something like it for [another project of mine](http://code.google.com/p/yomiko).  I've got feedformatter to the point where it fills the need for that other project so it's probably going to be a fairly low priority of mine to work on it any further.  I will certainly fix bugs if people report them, but I'm not likely to add new features often.

That said, there is scope for a _lot_ more work to be done on feedformatter.  More work on compatibility with feedparser as well as support for more formats, better validation, and about five billion unit tests for things like time string formats etc. would all be great.  I am happy to grant project membership to anybody interested in doing this sort of work once they satisfy me that they're not going to completely butcher the module - say by emailing me a useful and well-written patch for something.  Don't worry, my standards aren't that high.  Just drop me a line if you're interested.