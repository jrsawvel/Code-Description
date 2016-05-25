# Code Description


### My web apps as of March 2016


* **Parula** - toledotalk.com - message board with wiki and blog features. 2005.
* **Junco** - jothut.com - community site with social networking (following), wiki, and blog features, but jothut is configured as a single-user site. 2013. test site at junco.soupmode.com
* **ToledoWX** - toledoweather.info - JQuery mobile used to display weather info that's created at regular intervals by scripts that run in batch. 2013.
* **Kinglet** - soupmode.com - private, web-based messaging app that is part message board, microblog, and messaging. one-to-one or one-to-many. 2013-2014. test site at kinglet.soupmode.com
* **Grebe** - maketoledo.com, toledowinter.com, babyutoledo.com - multi-user blog tool. 2014. test site at grebe.soupmode.com.  a node.js client version exists at nodejs.soupmode.com. the node.js "client" code that obviously executes on the server accesses the grebe perl api.
* **Scaup** - crochet.soupmode.com - single-user MemEx (memory extender) app. a stream of notes and articles, sorted by modification date. 2015. the crochet site stores my crochet notes. test site at scaup.soupmode.com. 
* **Veery** - veeryclientperl.soupmode.com - another single-user MemEx stream app, similar to Scaup, but Veery is clearly separated into client and api code. the client code accesses the api code at veeryapiperl.soupmode.com. 2015. a nodejs client exists at veeryclientnodejs.soupmode.com.  
* **Waxwing** - waxwing.soupmode.com - image uploader and stream view app. client-side javascript reduces the image size and makes ajax call to server code, which stores the image on the file system. image can include a text description and hashtags. search exists. i wanted a simple way to upload an image on the phone and grab the image's url in order to embed the image within a post, using one of the above apps. 2015.
* **Article Preview** - article.soupmode.com - using a browser, markup is submitted and formatted html is returned. it supports markdown, multimarkdown, and textile. of course, html can be used too. it also contains a one-command api, which allows json to be submitted, which contains the markup, and json is returned, which contains the formatted post, along with other information, such as word count, reading time, etc. 2016.
* **Wren** - wren.soupmode.com, dad.soupmode.com, birdbrainsbrewing.com - static site blog generator. 2016. From the summer of 2014 to May 2016, birdbrainsbrewing.com was powered by Grebe code. In May 2016, the site's content was imported into Wren.


### My top-level domain name sites

* http://toledotalk.com
* http://toledoweather.info
* http://jothut.com
* http://soupmode.com
* http://maketoledo.com
* http://birdbrainsbrewing.com
* http://toledowinter.com
* http://babyutoledo.com


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


Tested the Ghost blog tool at: http://ghost.soupmode.com



### Usage sites

* http://waxwing.soupmode.com
* http://crochet.soupmode.com 
* http://dad.soupmode.com




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
* [TT-Chat](https://github.com/jrsawvel/TT-Chat) - simple, AJAX-based chat or live-blogging tool. Similar code is used as part of the "check-in" feature within the Junco app.
* [ToledoWX](https://github.com/jrsawvel/ToledoWX) - web-based weather app for the Toledo area. used at toledoweather.info.
* [Perl-ForecastIO](https://github.com/jrsawvel/Perl-ForecastIO) - This Perl module processes weather data, provided in JSON format by forecast.io.
* [Yo-Perl](https://github.com/jrsawvel/Yo-Perl) - Perl module that provides access to the Yo API.
 * [ForecastIO-Plus-Yo](https://github.com/jrsawvel/ForecastIO-Plus-Yo)
* [Article design ideas](https://github.com/jrsawvel/Article-Designs) - how I prefer content pages be  displayed
* [Wren](https://github.com/jrsawvel/Wren) - creating simple, fast-loading blog posts. This is a result of my article design ideas and Article Preview.



### Article design thoughts

* [Article Preview](https://github.com/jrsawvel/Article-Preview) - simple way to test out my article design thoughts.


