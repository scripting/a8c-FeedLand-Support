# Your FeedLand feed   

FeedLand takes a social media approach to feeds, like Twitter, Bluesky, Mastodon or Threads. 

Like those products FeedLand is two-way, so in addition to reading, you can also write. 

### Write your Hello World post

Choose <i>My feed</i> from the first menu.  

A new page opens with an edit box at the top and a place for a feed of items below. 

Click in the box and type something like <i>Hello World</i> and click the Post button.

In a moment the message you typed appears below in the list of the feed's items. 

### The edit box

<img src="https://imgs.scripting.com/2023/08/01/editbox2.png">

### Editing text

To edit the text in an item, click on the text in the list. The text then appears in the edit box. Make changes, when you're ready to publish click the <i>Update</i> button. The text changes both in the feed and in the list. 

If you decide you don't want to save your changes, click the Cancel button. 

Here's a <a href="https://imgs.scripting.com/2022/11/08/editboxbeingusedtoedittext.png">screen shot</a> of the edit box being used to edit an existing item.

In this mode, the text is not saved to the server as you make changes. 

### Notes

If you want more info about the published feed, click the (Feed) link next to the feed title. It will take you to the Feed Info page, which includes the URL of your feed. 

If your username is bullmancuso, this is <a href="http://data.feedland.com/feeds/bullmancuso.xml">where</a> your feed would be. 

Here's the <a href="https://feedland.com/?feedurl=https%3A%2F%2Fdata.feedland.com%2Ffeeds%2Fbullmancuso.xml">Feed Info page</a> for bullmancuso.

If you want to change the title or description of your blog, choose Settings from the right-most menu, click on the Feed tab and you can edit it there. <a href="https://imgs.scripting.com/2022/11/08/settingsdialogscreen.png">Screen shot</a>.

### Bookmarklets

We have two bookmarklets you can install from the sub-menu of the Tools menu, one for linkblogging, the other for subscribing to feeds.

Once installed, when you are on a web page that you want to link to from your feed, click the linkblogging bookmarklet. FeedLand will open in a new tab with the title of the page in the editbox and a link to the page in the link field in the Title, Link & Enclosure section of the editbox. 

Similarly, when you click on the subscribing bookmarklet, you're returned to FeedLand where you can subscribe to the feed for the page you were viewing, if we can find it.

If you select text on the page before clicking the bookmarklet, that text will appear in the editbox, and the title of the page will appear in the Title element of the TLE section of the editbox.

### Linkblogging from inside FeedLand

When you're looking at a timeline, there's a <i class="fa fa-retweet"></i> icon that's used to post the item to a linkblog. 

When you click that link it will be exactly as if you used the bookmarklet from outside of FeedLand.

### Enclosures

You can link to a media file from the Enclosure element in the Title, Link & Enclosure section. 

When your feed is saved, FeedLand generates an RSS &lt;enclosure> element, including a link to the file, its type and size.

### Markdown is just enough HTML

If you look at a <a href="http://data.feedland.com/feeds/scripting.xml">feed</a>, you'll see that the text is saved in the feed in both HTML and Markdown. 

We think more writing apps should support Markdown in feeds, because it would make the feed world richer and safer. 

More info <a href="http://scripting.com/2022/08/25/210902.html?title=markdownIsJustEnoughHtml">here</a>. 

