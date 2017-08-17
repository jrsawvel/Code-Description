# Code Description


### Info as of August 2017


* **Parula** - toledotalk.com - message board with wiki and blog features. 2005.
* **Junco** - jothut.com - community site with social networking (following), wiki, and blog features, but jothut is configured as a single-user site. 2013. test site at junco.soupmode.com
* **ToledoWX** - toledoweather.info - JQuery mobile used to display weather info that's created at regular intervals by scripts that run in batch. 2013.
* **Kinglet** - soupmode.com - private, web-based messaging app that is part message board, microblog, and messaging. one-to-one or one-to-many. 2013-2014. test site at kinglet.soupmode.com
* **Grebe** - maketoledo.com, toledowinter.com, babyutoledo.com - multi-user blog tool. 2014. test site at grebe.soupmode.com.  a node.js client version exists at nodejs.soupmode.com. the node.js "client" code that obviously executes on the server accesses the grebe perl api.
* **Scaup** - crochet.soupmode.com - single-user MemEx (memory extender) app. a stream of notes and articles, sorted by modification date. 2015. the crochet site stores my crochet notes. test site at scaup.soupmode.com. 
* **Veery** - veeryclientperl.soupmode.com - another single-user MemEx stream app, similar to Scaup, but Veery is clearly separated into client and api code. the client code accesses the api code at veeryapiperl.soupmode.com. 2015. a nodejs client exists at veeryclientnodejs.soupmode.com.  in 2017, i added veeryapinodejs.soupmode.com.
* **Waxwing** - waxwing.soupmode.com - image uploader and stream view app. client-side javascript reduces the image size and makes ajax call to server code, which stores the image on the file system. image can include a text description and hashtags. search exists. i wanted a simple way to upload an image on the phone and grab the image's url in order to embed the image within a post, using one of the above apps. 2015.
* **Article Preview** - article.soupmode.com - using a browser, markup is submitted and formatted html is returned. it supports markdown, multimarkdown, and textile. of course, html can be used too. it also contains a one-command api, which allows json to be submitted, which contains the markup, and json is returned, which contains the formatted post, along with other information, such as word count, reading time, etc. 2016.
* **Wren** - wren.soupmode.com, boghop.com, birdbrainsbrewing.com, zwdqwr2p2xwkpbyv.onion, gopher://boghop.com - static site blog generator. 2016. From the summer of 2014 to May 2016, birdbrainsbrewing.com was powered by Grebe code. In May 2016, the site's content was imported into Wren. On my home Linux computer, I installed Tor, and when my computer is powered on, it hosts a .onion site that contains HTML pages, generated by Wren. Just playing around. The gopher site is also for testing.
* **Tanager** - My Junco, Grebe, Scaup, Veery, and Wren web publishing apps have the option to use a simple, JavaScript-based “editor” for creating and updating posts. In 2013, I started with this person’s code <borgar.github.io/textile-js>. I modified the original code significantly to support my needs, including the removal of the live preview. I prefer to let the server code do the formatting. My customized version accesses the API endpoints in my web publishing apps. Using REST and JSON, the editor sends markup to the server, and it receives back the formatted HTML. I also added additional functionality to the JavaScript code. The original code used jQuery. When I added my changes, I used the small minified.js framework. Tanager, however, is a rewrite that uses vanilla JavaScript. No frameworks. I'm using it with my Wren static site generator. 2017.
* **Warbler** - warbler.soupmode.com - Webmention-based message board. All thread starter posts and commens are Webmentions where users create the posts on their own websites or web presences, and then the users copy the URLs to the posts and paste them into a Warbler-powered website. Warbler displays excerpts of the posts. Warbler also displays links to the original posts. More info about the Webmention can be found at <https://indieweb.org/webmention>.




### My top-level domain name sites

* http://toledotalk.com
* http://toledoweather.info
* http://jothut.com
* http://soupmode.com
* http://maketoledo.com
* http://birdbrainsbrewing.com
* http://toledowinter.com
* http://babyutoledo.com
* http://boghop.com
* gopher://boghop.net
* http://perchwire.com - test building a website with Jekyll + GitHub Pages + Prose.io
* http://sawv.org


### Test sites

* http://junco.soupmode.com
* http://kinglet.soupmode.com
* http://grebe.soupmode.com
* http://nodejs.soupmode.com
* http://testcode.soupmode.com
* http://scaup.soupmode.com
* http://veeryclientperl.soupmode.com
* http://veeryclientnodejs.soupmode.com
 * both veery clients access the api code at http://veeryapiperl.soupmode.com
* http://article.soupmode.com
* http://wren.soupmode.com
* http://zwdqwr2p2xwkpbyv.onion
* gopher://gopher.soupmode.com
* http://warbler.soupmode.com


Tested the Ghost blog tool at: http://ghost.soupmode.com


### Usage subdomain sites

These are not test sites.

* http://waxwing.soupmode.com
* http://crochet.soupmode.com 



### My Source Code

* [Junco](https://github.com/jrsawvel/Junco) - used at JotHut.com
* [Kinglet](https://github.com/jrsawvel/Kinglet) - used at Soupmode.com
* [Grebe](https://github.com/jrsawvel/Grebe) - used at MakeToledo.com,  BirdBrainsBrewing.com, ToledoWinter.com, and BabyUToledo.com
* [Grebe-Client-NodeJS](https://github.com/jrsawvel/Grebe-Client-NodeJS) - Node.JS "client" code that consumes the [Grebe API.](https://github.com/jrsawvel/Grebe/blob/master/docs/api.md)
* [Waxwing](https://github.com/jrsawvel/Waxwing) - client-side javascript image resizer and uploader to a stream view. waxwing.soupmode.com
* [Scaup](https://github.com/jrsawvel/Scaup) - web publishing tool that uses CouchDB and Elasticsearch. used at scaup.soupmode.com and crochet.soupmode.com.
* **Veery** - another web publishing tool that uses CouchDB and Elasticsearch, but the app is divided into client and API codebases.
  * [Veery-API-Perl](https://github.com/jrsawvel/Veery-API-Perl)
  * [Veery-Client-Perl](https://github.com/jrsawvel/Veery-Client-Perl)
  * [Veery-Client-NodeJS](https://github.com/jrsawvel/Veery-Client-NodeJS)
  * [Veery-API-NodeJS](https://github.com/jrsawvel/Veery-API-NodeJS)
* [TT-Chat](https://github.com/jrsawvel/TT-Chat) - simple, AJAX-based chat or live-blogging tool. Similar code is used as part of the "check-in" feature within the Junco app.
* [ToledoWX](https://github.com/jrsawvel/ToledoWX) - web-based weather app for the Toledo area. used at toledoweather.info.
* [Perl-ForecastIO](https://github.com/jrsawvel/Perl-ForecastIO) - This Perl module processes weather data, provided in JSON format by forecast.io.
* [Yo-Perl](https://github.com/jrsawvel/Yo-Perl) - Perl module that provides access to the Yo API.
 * [ForecastIO-Plus-Yo](https://github.com/jrsawvel/ForecastIO-Plus-Yo)
* [Article design ideas](https://github.com/jrsawvel/Article-Designs) - how I prefer content pages be  displayed
* [Wren](https://github.com/jrsawvel/Wren) - SSG (static site generator), creating simple, fast-loading web posts. This is a result of my article design ideas and Article Preview.
* [Tanager](https://github.com/jrsawvel/Tanager) - JavaScript "editor" written in plain, vanilla JavaScript. Communicates with server code with REST AND JSON. 
* [Warbler](https://github.com/jrsawvel/Warbler) - Webmention-based message board.


### Article design thoughts

* [Article Preview](https://github.com/jrsawvel/Article-Preview) - simple way to test out my article design thoughts.

This page was updated from within GitHub's simple web editing interface.
