# Extras  

Features that don't yet have their own docs pages.

### JSON-specified news products

As of January 2024, you can create specs for news products using JSON in addition to OPML. The data supplied is basically the same, the format is different. 

All the features are supported except <a href="https://docs.feedland.com/newsproducts.md#the-html-section">replacing the HTML</a> in the page. That is not yet possible in JSON-specified products. 

An example of a news product that is specified in JSON is <a href="https://news.scripting.com/">news.scripting.com</a>.

Here's the <a href="http://scripting.com/code/newsproducthome/newsscriptingcom2.json">JSON spec</a> for that site.

A few notes:

1. The values for <i>script</i> and <i>style</i> can be either a string, or an array of strings. If you have more than one line of code or styles, use an array. 

2. In the <a href="http://scripting.com/code/newsproducthome/newsscriptingcom2.json">example</a>, style is an array and script is a string.

3. There is <a href="https://github.com/scripting/pagePark/blob/master/worknotes.md#1824-93820-am-by-dw">support in PagePark</a> for this format, in addition to the OPML version. 

4. If you have questions or comments, <a href="https://github.com/scripting/feedlandSupport/issues/234">post a note here</a>. 

### Bookmarks in FeedLand

This feature goes back a long way, to the beginnings of Frontier and <a href="http://scripting.com/autowebdocs/menusharingwalkthru_148.html">Menu Sharing</a> and through <a href="http://docserver.scripting.com/drummer/general.opml#1629044069000">Drummer</a>, whose Bookmarks menu is imho a truly revolutionary thing. 

Here's a <a href="https://imgs.scripting.com/2022/12/31/feedLandBookmarksDaveScreen.png">screen shot</a> of my current Bookmarks menu in Drummer. You can see I use it a lot. I expect your bookmarks menu will look something like that before too long. 

There are two ways to create a bookmark.

When you're looking at a news item in a _river_ timeline, there's a new icon at the bottom, that <a href="https://imgs.scripting.com/2022/12/31/feedLandItemBookmarkIcon.png">looks like</a> a bookmark. Click it. A dialog confirms that you want to add the bookmark. Then the Bookmarks editor window opens with the new bookmark added at the top. You can edit the text, and use the outliner reorganizing commands to move it where you want.  When you're finished, click OK and the menu outline is saved on the server, and the menu is automatically rebuilt with the new bookmark where you put it.

If you're at a page in FeedLand that you want to get back to easily, say an interesting person's feed list, choose <i>Add Bookmark</i> at the top of the Bookmarks menu. A dialog confirms you want to add this page to the menu. And the process of editing and placing the bookmark works exactly as it does for when creating a bookmark from a timeline.

The outliner is the same one as in Drummer. For an idea of how to use it see the <a href="http://outlinerhowto.opml.org/">Outliner howto</a> document. 

### Feeds of Likes

Each user can have a feed of all the items they <i>liked</i> in FeedLand. 

You must be logged in to be able to Like something. 

<img src="https://imgs.scripting.com/2022/11/01/likescreen.png">

Click the thumb icon to like an item.

When you like something it is added to your feed of likes, which you can then subscribe to <a href="http://feedland.org/?feedurl=http://data.feedland.com/likes/davewiner.xml">in FeedLand</a> or any other <a href="http://xmlviewer.scripting.com/?url=http%3A%2F%2Fdata.feedland.com%2Flikes%2Fdavewiner.xml">app</a> that can read an RSS 2.0 feed. 

You have to like something before you actually have the feed. FeedLand won't create it until you like something. 

Here's the address for my feed of likes: <a href="http://xmlviewer.scripting.com/?url=http%3A%2F%2Fdata.feedland.com%2Flikes%2Fdavewiner.xml">http://data.feedland.com/likes/davewiner.xml</a>.

And here's the <a href="http://feedland.org/?feedurl=http%3A%2F%2Fdata.feedland.com%2Flikes%2Fdavewiner.xml">Feed Info page</a> for that feed. 

Like icons appear in news pages. To see one of these pages, choose <i>My news</i> from the first menu.

Here's <a href="http://feedland.org/?river=true&screenname=davewiner&catname=all">my news page</a>. If you're logged in you can like items on that page. 

