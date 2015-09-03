# Auto AppCache example

An example using [Surge](https://surge.sh)’s Auto AppCache to building offline web apps

## Getting started

- The promise of the Application Cache
-- Why you’d want an app offline
-- Why you’d want a static site offine (Slides, docs, read-it-later)
- The problems of Application Cache…it’s really, really challenging to maintain properly, is really picky about tiny details, and breaks if a single thing is wrong
- We build an `auto.appcache` file for you automatically, so you don’t have to worry about the challenging parts, and instead can focus on the fun parts: getting you app or static site to run offline
- Reference the `auto.appcahce` file in the `manifest` attribute in the `<html>` tag
- Clean URLs work automatically
- Index page is your fallback
- Don’t add the `manifest.appcache` attribute to the `200.html` file (?)
- Script prevents jumping out of Standalone mode on mobile Safari (still having an inconsistent experience with this on harpjs.com, but it works in this demo)

## License

[The MIT License (MIT)](LICENSE.md)

Copyright © 2015 [Chloi Inc.](http://chloi.io)
