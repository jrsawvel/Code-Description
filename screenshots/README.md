# Screenshots of My Web Apps



### Parula

Used at http://toledotalk.com since 2005. ToledoTalk.com began in January 2003.

View of the site with the browser resized to approximate a mobile view.

![](https://c2.staticflickr.com/6/5816/22157377490_77d190acd8.jpg)


Desktop view of creating a new thread post.

![](https://c2.staticflickr.com/6/5697/22345138575_10016c75ba_z.jpg)


Home page view when logged in.

![](https://c2.staticflickr.com/6/5789/22331644482_b3e0b1e89e_z.jpg)





### Waxwing

Used at http://waxwing.soupmode.com

Small image uploader app with stream views. A post can also contain text, including hashtags. String search and hashtag search exist. Browser-based JavaScript resizes the image before uploading.

Adding or uploading an image. This works fine on a phone too, except with versions of iOS prior to version 8.

![](https://c1.staticflickr.com/1/698/22318802156_0a1b73b58b_z.jpg)


Desktop view of one of the posts or an  "article" page.

![](https://c1.staticflickr.com/1/695/22157334380_e8a7b3e3f4_z.jpg)


Another view of a post page.

![](https://c2.staticflickr.com/6/5829/22157056568_29459619bc_z.jpg)



### Scaup

Used at http://crochet.soupmode.com to track my crochet notes.

Scaup is a small, single-user web publishing app. Scaup stream views display a mix of articles and notes.

Desktop view of the home page stream while not logged into the app. If logged-in, then a small text area box would be positioned at the top of the site to allow fast posting of notes or links.

![](https://c1.staticflickr.com/1/691/22332248702_be9a77a49b_z.jpg)



### Grebe

Used at:

* http://maketoledo.com
* http://toledowinter.com
* http://babyutoledo.com

Grebe is a multi-user blogging tool or web publishing app.

The default setup is to display only article pages on the home page, sorted by updated date from youngest to oldest. Standard blog view.

A notes stream is displayed separately. This screenshot shows the stream of notes while logged in.

![](https://c2.staticflickr.com/6/5724/22355827481_d82a53bd46_z.jpg)

In the above image, the icons shown at the top from left to right represent:

* grey house : link back to home page of articles.
* blue gear : link to the user's profile page that contains links to account or profile settings for the user when logged in.
* blue paper : displays the notes stream shown above.
* blue pencil : large a larger text area box that allows more room for writing. On this page is a link to the enhanced writing mode, which is a JavaScript-based editor, which is what I'm using to create this document.
* grey magnifying glass : link to a page that displays a text input field for text to be searched.

The blue icon images appear when the user is logged into the app.



ToledoWinter.com home page while logged in.

![](https://c2.staticflickr.com/6/5730/21723680553_93d1167ab1_z.jpg)


### Tags

List hashtags and their counts alphabetically by tag name.

![](https://c2.staticflickr.com/6/5624/21724113483_255f824659_z.jpg)


List hashtags and their counts by tag count, highest to lowest.

![](https://c2.staticflickr.com/6/5765/21724113983_5c6e61b8dc_z.jpg)




### Veery

Similar to Scaup, except the code is separated into API and Client. Currently, the API code exists in Perl, but a version created with Go is planned. Client code exists in Perl and Node.js.


To log in, only an email address is submitted that matches the author's info that's stored in CouchDB. Veery send a link that when clicked will log the user into the app. The login link will only work one time.

![](https://c2.staticflickr.com/6/5745/22355624641_8b8c300b2e_z.jpg)


Home page stream view when logged in. The small text area box can be used to create an article or note.

![](https://c2.staticflickr.com/6/5773/22345023035_12ffe69937_z.jpg)


This is the larger text area box for creating a note or article. This is accessed after clicking the 'W' link in the above screenshot. Clicking the `[|]` link in the above screen shot would bring up the JavaScript editor or enhanced writing mode.

![](https://c2.staticflickr.com/6/5651/22345023045_67be9ca595_z.jpg)



<br />Desktop view of an article page.

![](https://c2.staticflickr.com/6/5695/22355775881_114dff6b53_z.jpg)



### JavaScript Editor

"Editor" may be an inappropriate term to use describe this browser-based JavaScript tool. This enhanced writing environment is used with Junco, Grebe, Scaup, and Veery web publishing apps.

The original code is found at:
http://borgar.github.io/textile-js

The original JavaScript provides a Textile live preview editor. The code splits the screen. An author writes markup in the left pane while the right pane provides a live preview of the formatted text. The brower JavaScript converted the Textile markup to HTML.

When testing the code in the summer of 2013, I found the flashing of the live preview annoying and distracting as I typed, since I could see the live preview out of the corner of my eye.

I greatly modified the code. I used the small minified.js framework to make my changes.

I eliminated the live preview. All my apps contain custom formatting options along with supporting Markdown, MultiMarkdown, and Textile, and did not want to try to add all my formatting options to client-side JavaScript. For the Junco code that contains Wiki functionality, server-side formatting was required.

Also to borgar's JavaScript app, I added the single screen option. I can switch from split screen to single screen for a bigger writing area, and then I can switch back to splits screen. 

I added a line of buttons across the top to switch to single screen or split screen and to save or preview a post.

And I added keyboard shortcuts to the JavaScript editor for use with a keyboard.

* ctrl-s = save
* ctrl-p = preview (i don't use a printer, so this is fine for me). this sends markup to the server for formatting, and then the HTML is displayed in the right pane. if writing in single-screen mode, then the screen switches to the preview also in single-screen mode.
* ctrl-j = simpler, single screen view that removes the line of buttons at the top
* ctrl-h = provides a tiny, simplified window for writing that is only five lines tall 
* ctrl-d = switches the default display from black text on white background to light grey text on a black background
* ctrl-b = return to the standard, split-screen view with the small row of buttons across the top


The editor works fine on the phone's browser. Obviously, it's easier to write on the phone with the editor in single screen mode.


The default writing environment. Droid Sans Mono font is used in the writing pane (left). Open Sans font is used in the HTML preview pane (right). The button with the arrows pointing right is used to switch to single screen mode. The button with the arrows point left is used to switch to split screen mode.

![](https://c2.staticflickr.com/6/5740/22319004206_d8d5623a12_z.jpg)


Single screen mode for writing.

![](https://c1.staticflickr.com/1/749/22319046156_c8f246cf6b_z.jpg)


Single screen mode for previewing a post.

![](https://c1.staticflickr.com/1/620/22157337188_65fa9fb1c4_z.jpg)


This is a desktop / laptop view after hitting ctrl-j to create a simplified writing environment. No buttons. 

![](https://c1.staticflickr.com/1/613/22157039920_d16dc37249_z.jpg)


This is a desktop / laptop view after hitting ctrl-d to change the default colors when using the simplified writing environment.

![](https://c1.staticflickr.com/1/675/22355736491_4b81679023_z.jpg)



This is a desktop / laptop view after hitting ctrl-h to reduce the writing window to only five lines tall.

![](https://c1.staticflickr.com/1/750/21723990313_06f7a469a0_z.jpg)



### Kinglet

Used at http://soupmode.com

It's a private, web-based messaging app. It's sort of a cross between messaging, email, and a message board.


Show the list of my discussion threads.

![](https://c1.staticflickr.com/1/679/22344904505_037aaee260_z.jpg)


Start a new message thread that will either be sent only to me for a truly private notes thread, or I can include one or more other users for a group message thread.

![](https://c1.staticflickr.com/1/596/22331885362_a29837dd64_z.jpg)


<br />When logged in, this is an example of how the home page would appear.

![](https://c2.staticflickr.com/6/5689/22331643762_9e5fb3c18f_z.jpg)




### Junco

Used at http://jothut.com

Junco is a multi-user community app that supports following users, following tags, replies, etc. But for jothut.com, I switched it to single-user mode.

Home page view when I'm logged in. If the app ran in multi-user mode, this would not be the default home page view.

![](https://c1.staticflickr.com/1/744/22344767405_93b57ae7e8_z.jpg)


<br />I spend most of my time in the stream view, which is similar to the stream view listed above for Veery. It's also used at Scaup, and it's the view used for the notes section in Grebe.

![](https://c2.staticflickr.com/6/5699/22331841642_6df5c355cb_z.jpg)


<br />My profile page. The items listed in the light blue background are only shown to me when I'm logged in.

![](https://c2.staticflickr.com/6/5696/22156837100_3f9b4c63a9_z.jpg)



### ToledoWX

Used at http://toledoweather.info

jQuery Mobile is used to display pages.

Desktop view of the home page.  
![](https://c1.staticflickr.com/1/601/22331743722_a5e0d3b56c_z.jpg)


Desktop view of the Forecast.io info page.  
![](https://c1.staticflickr.com/1/699/22259563179_c9a4e04823_c.jpg)


Views on a phone.

![](https://c2.staticflickr.com/8/7524/27191794613_c44f96e2a6_z.jpg)


<br />![](https://c2.staticflickr.com/8/7415/27802935865_1f03674930_z.jpg)


<br />![](https://c2.staticflickr.com/8/7654/27191668773_c751982f48_z.jpg)


<br />![](https://c2.staticflickr.com/8/7491/27587155722_b38b83b374_z.jpg)




### Yo Notifications

The [Yo service](http://www.justyo.co/) offers an API. I use my [Yo-Perl](https://github.com/jrsawvel/Yo-Perl) module at ToledoTalk.com and ToledoWeather.info to send notifications to my phone. When a new post is made at Toledo Talk, I receive a Yo. When Forecast.io data predicts heavy rain for the area, ToledoWeather.info sends a Yo.

![](https://c2.staticflickr.com/8/7425/27409297470_21e48d1edc_z.jpg)

<br />![](https://c2.staticflickr.com/8/7393/27074154454_2f873fab39_z.jpg)





### Baby University

Powered by Grebe.

Screenshot of the homepage as of early November 2015.

![](https://c2.staticflickr.com/6/5768/22783935549_3fb1868151_c.jpg)


Screenshots of the homepage as of 2016. The buttons are now mouse-over-dropdown menus.

![](https://c2.staticflickr.com/8/7441/27652053586_1511cbbaef_c.jpg)


Mobile versions of the most recent homepage.

![](https://c2.staticflickr.com/8/7176/27586013392_43f9e0f25c_z.jpg)

<br />![](https://c2.staticflickr.com/8/7434/27612102151_1cac333c15_z.jpg)

<br />![](https://c2.staticflickr.com/8/7329/27686709835_16f680163c_z.jpg)




### My iPhone 

Screen grabs of links to my web apps or sites, saved to the phone's home screen and within the Safari web browser. (iOS 7)

![](https://c2.staticflickr.com/8/7132/27803067245_379d81a3ff_z.jpg)

<br />![](https://c2.staticflickr.com/8/7243/27524641230_5275a56a36_z.jpg)

<br />![](https://c2.staticflickr.com/8/7416/27803064515_0103c757e9_z.jpg)




### Wren

Used at http://birdbrainsbrewing.com

[screenshots needed]



### Map Mashups


Last decade on the ToledoTalk.com server, I created a few [map mashups](http://toledotalk.com/cgi-bin/tt.pl/article/2114/Lewiki_Mashups) that combined data with Google maps.

I built [my first map mashup](http://www.toledotalk.com/cgi-bin/comments.pl/21/1376) in 2005 that mapped Lucas County registered sex offenders, using data from the sheriff's department.

A user could enter an address to show the location of nearby registered sex offenders. I had programmed the addresses for all the county library locations into the database and some of the TPS elementary schools. The user could filter by classification, zip code, city, and last name.

But I unplugged the app a few years later because I received multiple lawsuit threats. I used government data. Even when I explained that the person was still in the latest file produced by the sheriff, I still received the threats.

The last time that I processed the data was in 2008. I've disabled viewing of that map app. The other map mashups don't display content anymore because of tech changes by Google.

Some old screenshots from 2008:

Home Page  
![](http://farm4.staticflickr.com/3735/9315081518_9a150e3587.jpg)


Offenders that lived in 43613  
![](http://farm6.staticflickr.com/5520/9312295331_2f4e026207_n.jpg)


The Tier III (Sexual Predators) in the county  
![](http://farm4.staticflickr.com/3789/9315081482_fa3dc76466_n.jpg)

Obviously, it was possible to zoom in on the maps and click the push-pins for details, which should information for each individual. The names of the registered offenders were also displayed on the web page outside of the map area.





### ToDo 

Add screenshots for the following areas:

* bottom of a veery home page
* more phone screenshots
* toledo talk home page, logged in, new comments to read
* wren

https://www.flickr.com/photos/131621939@N03/tags/screenshot/

