# Porting Destiny Item Manager (DIM) to Firefox with WebExtensions
In October of last year, while attending the Fronteers15 conference in the Netherlands, I was introduced to Mozilla's Web Extensions API. The project was of some interest to be: it aims to ease the development of cross-browser add-ons by supporting the Chrome Extension API in Firefox. Having just commited to implementing a Firefox version of [DIM](https://github.com/DestinyItemManager/DIM), I was struggling to hammer it into the square hole that was the Firefox add-on sdk. The purpose of this post is to pass on the knowledge I learned in the hopes that I can make life easier for other developers in the future.

As of 2016-04-16 Web Extensions are available in Firefox 45 in an alpha state. Not all of the Chrome API's are available, but be sure to check [http://www.arewewebextensionsyet.com/](http://www.arewewebextensionsyet.com/) for the latest updates.

# Initial Preparation 
* Firstly we need a copy of Firefox. I chose the [Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) but any version after version 45 should work.
* Secondly we need a copy of DIM itself `git clone https://github.com/DestinyItemManager/DIM.git`
* Third, save this to git






