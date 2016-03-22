# StrapDown.js (on GitHub)
[StrapDown.js](https://naereen.github.io/StrapDown.js/) is an awesome web script to write nice-looking webpages in pure Markdown, with no server side compilation.

----

## Features
**StrapDown.js** is already pretty advanced:

 1. *Directly write your documents in Markdown*, and let the browser do the boring *compilation* steps,
 2. no need for CSS, theming or painful styling: *StrapDown.js* is already *friggin' beautiful*, and *responsive*,
 3. *quick* and *secure*, thanks to *GitHub* and their great SSL support. Note : You can also use [https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js](https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js) to load the script from a quick and secure (HTTPS-aware) CDN.
 4. comes with many examples: <a href="example1.html" title="Example 1">first</a>, <a href="example2.html" title="Example 2">second</a>, <a href="example3.html" title="Example 3">third</a>, <a href="example4.html" title="Example 4">4th</a>, <a href="example5.html" title="Example 5">5th</a>, <a href="example6.html" title="Example 6">6th</a>, <a href="example7.html" title="Example 7">7th</a>...
 5. an almost perfect support for *text-only* browsers (as w3m, links, or elinks): *pure Markdown* is simpler to read than complicated HTML full of javascript, images (or worse),
 6. no external dependencies other than itself (and [MathJax](http://www.mathjax.org/) if you want to include it),
 7. no spying, no logging, no external leaking of your pages (and [Google Analytics with a 1px beacon image](http://perso.crans.org/besson/beacon.html) can be included with an option,
 8. an excellent support of [*MathJax*](http://www.mathjax.org/), as shown in [this example](example3.html) or [that one](example5.html),
 9. and, the last but not the least, an *experimental* embedding of the awesome [SquirtFR](http://lbesson.bitbucket.org/squirt) bookmarklet to read *as quickly as Lucky Luke*.


## Drawbacks?
But there is also have a few things you need to know before using it:

 1. It might get slow for *very long* pages, even if a **3000-line** document is handled very well and quickl ([you can test by yourself with this long document](3000.html)),
 2. a reduced support for browsers *without javascript* or *with javascript disabled* (the pages are still readable, but really *ugly*),
 3. hosted on [GitHub](https://github.com/) and served by [rawgit](https://rawgit.com), which are wonderful but *might* not be always available.

## Concretely
Concretely, GitHub is [always](http://status.github.com/) *up*, *secured* and *quick* (oooh, and it is also awesome, completely free, and awesome too). Yeah, *is it so awesome* that I had to say it *twice*, you read it correctly!

But if you prefer, feel free to download the project (with [StrapDown.js.zip](https://bitbucket.org/lbesson/lbesson.bitbucket.org/downloads/StrapDown.js.zip)) and upload it somewhere on your own server, or locally on your machine.

As the script is hosted on [GitHub](https://github.com/Naereen/StrapDown.js/), it can be loaded *quickly* and *securely* from [cdn.rawgit.com](https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js): [https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js](https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js)!

> ### A quick "thank you" to the [initial project](https://github.com/arturadib/strapdown/)
> My version of StrapDown.js is a fork of [strapdownjs.com](http://strapdownjs.com), a cool project that [kinda seems dead by now](https://github.com/arturadib/strapdown/graphs/contributors).

----

## Examples
### Here is a first demo:
![First demo](demo1.png "First lines of the index.html page")

----

### [This page](http://lbesson.bitbucket.org/md/index.html) explains how to use StrapDown.js:
![Second demo](demo2.png "Demo of the demo!")

----

### There is also many [different themes](https://github.com/Naereen/StrapDown.js/tree/master/themes/):
![Third demo](demo3.png "Small example with the Cyborg theme")

----

### StrapDown.js supports [MathJax](https://www.mathjax.org/), and it's really easy to use!
![Forth demo](demo4.png "First lines of the index.html page")

----

### StrapDown.js also supports [MarkDown tables](https://help.github.com/articles/github-flavored-markdown/#tables):
![Fifth demo](demo5.png "First lines of the index.html page")

----

### And as any web-based document, a StrapDown.js powered HTML page can include any Javascript script, like this example which shows a research bar for a table:
![Sixth demo](demo6.png "First lines of the index.html page")

----

## More details
More details on [http://lbesson.bitbucket.org/md/index.html](http://lbesson.bitbucket.org/md/index.html), with examples and extra explanations.

----

## About
### Hacked by [Lilian Besson](https://github.com/Naereen) (Naereen).

### Languages
 - [JavaScript](https://en.wikipedia.org/wiki/Javascript),
 - [HTML 5](https://en.wikipedia.org/wiki/HTML) and [CSS 3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets).

### License
This project is released under the **MIT license**, for more details, take a look at the [LICENSE](http://lbesson.mit-license.org/) file in the source.

[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/StrapDown.js/README.md?pixel)](https://github.com/Naereen/StrapDown.js)