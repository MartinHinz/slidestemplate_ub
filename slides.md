---
title: Slides Template
separator: <!--s-->
verticalSeparator: <!--v-->
theme: white
revealOptions:
    transition: 'convex'
---

<link rel="stylesheet" href="css/style.css" id="theme">
<link rel="stylesheet" href="css/customize.css" id="theme">
<link rel="stylesheet" href="css/default-fonts.css" id="theme">

# Local

* clone the repo
* edit the `slides.md` file
* then:
```
npm install
npm run presentation
```

Note: This is a speaker note, you need node 6.x installed

<!--s-->

## GitHub Pages

* fork the repo
* setup a build in travis for the fork - don't forget the env var with your personal access token
* edit the `slides.md` file
* push to github
* view presentation on GitHub - in the project pages for your repo

<!--v-->

# References

* [reveal-md](https://github.com/webpro/reveal-md)
* [reveal.js](http://lab.hakim.se/reveal-js)
* [GitHub Pages](https://pages.github.com)
* [Travis CI](https://travis-ci.org)
* [This template](https://github.com/martinmurphy/slidestemplate)
