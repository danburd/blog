---
title: Gratitude for my feed reader
summary: An appreciation of Atom/RSS feeds and the programs that read them.
date: 2023-10-08T12:00:00-04:00
images: ["files/freshrss-screenshot.png"]
cover:
    image: "files/freshrss-screenshot.png"
    relative: true
    hiddenInSingle: true
---

I still remember the first time I used a feed reader. I was still in high school in 2004 when I used the Sage RSS reader extension for Firefox to load new articles on the BBC World News website. It was revolutionary - it showed a list of news articles in chronological order, highlighting which articles I hadn't seen yet. I didn't have to view articles through the website, which showed the articles in an unhelpful order and highlighted stories I didn't consider important. From that point on I didn't want to read news or blogs any other way.

And for awhile, I didn't. A year later, [Google Reader](https://en.wikipedia.org/wiki/Google_Reader) was released, which brought RSS and Atom feeds to a larger audience. Gradually, many more people starting using them, even those who didn't have any technical background. Most websites also offered RSS or Atom feeds as well. Every blog had one (blogs were big back then) and most news websites also offered them.

I recall the years after I graduated college (2009-2013) as being the heyday of feed readers. Websites prominently displayed the RSS logo to prompt visitors to subscribe. Many of their feeds contained the full content of their articles, so that visiting many websites was unnecessary. Almost all of my friends used Google Reader; they would use the "share" feature for interesting articles, which would then show up in my feed, and I would occasionally do the same. Google Reader was sort of our "morning coffee" in that it was the first website we'd visit in the morning to get a sense of what was new in the world. It was a tab we kept open at work while we labored away at our entry-level jobs - the shared articles kept us somewhat connected during these hours, without being unduly distracting or unprofessional. Pubsubhubbub, now called [Websub](https://en.wikipedia.org/wiki/WebSub), allowed (and still allows) for subscribers' feed readers to receive real-time updates when a blog to which they subscribe has a new post.

{{< figresize o=720x src="files/google-reader-page.png" caption="The good old days. Screenshot source: https://feeder.co/knowledge-base/rss-basics/google-reader/" >}}

And then everything changed. Google Reader was shut down in 2013. Most people stopped using RSS/Atom seemingly overnight. Some said they would get their updates from Facebook or other social media, which seemed impossible to me as those services didn't offer an exhaustive chronological feed and instead put users at the whim of an algorithm. Others, including myself, switched to other feed readers: I switched briefly to Feedly before settling on Inoreader for many years.

But many websites responded to users' preferences and stopped offering feeds as well. News websites were the first to go. Many news sources correctly realized that including the full content of news articles in their feeds was bringing down their website traffic, and started only including headlines and summaries in their feeds. Many others scrapped their feeds altogether. Some sites that kept their feeds reduced the number of feeds they offered. Almost all news websites stopped advertising their feeds on their homepage - a drastic change over a brief period of time.

I continued to use a feed reader for blogs and tech websites, neither of which ever stopped making feeds available. But due to the declining availability of feeds on news websites, and Inoreader's infrequent polling time compared to Google Reader, I didn't find it easy to keep up with the news using a feed reader. I used Google News and browsed individual news sites, but these mostly highlighted the same news topics repeatedly. I switched to Tweetdeck for a few years; subscribing to wire services like the Associated Press on there was fantastic for breaking news, but it wasn't always easy to catch up on what I'd missed if I stepped away for awhile. Being reliant on Twitter as a medium for receiving information also became increasingly problematic.

---

Two years ago I decided to double-down on feeds by running my own feed reader. I had grown weary of relying on algorithms and intermediary services for information. I bought a mini PC to act as a server, and I installed [FreshRSS](https://freshrss.org) on it.

It was a breath of fresh air. I felt like I had control over the internet for the first time in years. The feed reader gathered up all of the information I wanted, and none that I didn't. I could read the news as a series of headlines in chronological order, rather than a human or algorithm deciding what it thought was the most important news and putting at the top of the page in big font. There were no tracking links to detect who I was.

I've organized news into categories: Local, World, U.S., Politics, Science/Tech, Work (related to my job), and Features (long-form writing). However, most feeds fall into a final category: Seldom, which includes all feeds that updated less often than once per day. This encompasses most non-news feeds: all personal and tech blogs, software updates, local organizations and museums' websites and newsletters, YouTube feeds, and school and PTA updates.

{{< figresize o=720x src="files/freshrss-screenshot.png" caption="Reading the news is a favorite pastime of mine, even when the news is grim. I still want to be informed." >}}

Every site that uses Wordpress, Drupal, and many other content management systems publish a feed unless explicitly turned off. The result is that many websites offer feeds without their owners apparently realizing it. This includes websites for my employer and my kids' school. I am frequently able to tell my coworkers and my co-parents about updates that they couldn't have noticed without repeatedly checking the website. Sometimes these updates aren't even published on the homepage - the feed may be the only way to access their URL and content. In these cases, the feed reader really feels like a secret weapon.

Many organizations offer newsletters rather than feeds these days. For those I use a free and open source service called [Kill the Newsletter](https://kill-the-newsletter.com/), which provides an email address and a feed URL upon request, effectively turning a newsletter into a feed. I can subscribe to newsletters without ever having to give out my personal email address, and I can unsubscribe at will without fear of spam. This is a fantastic service that keeps the user in control.

One year ago [FreshRSS got turbocharged with a new feature](https://github.com/FreshRSS/FreshRSS/releases/tag/1.20.0): web scraping. I could program my feed reader to identify and download new content from websites that don't even offer feeds. This is critical for getting content from a few websites, including those for news wires like the Associated Press and Reuters that long ago stopped offering feeds. With this feature, I effectively have a news wire of my own.

And that's the story so far. I love my feed reader. I encourage others to use feed readers, as I honestly believe the world would be far better off if more individuals used a chronological feed rather than an algorithmic one to absorb information. But I know it's a lot to set up your own feed reader and the free third-party feed readers usually charge for features like filters, unlimited feeds, lower polling times, and scraping - the very features that make the technology so useful. I've come to terms with being the only person I know to use a feed reader, but I still hope for a comeback.
