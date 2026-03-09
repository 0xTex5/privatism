# Privatism
#### how to privatize your digital life 101:

## Prerequisites
You should have decent computer experience, such as browsing the web, reading emails, and deleting files off of your computer.
You should be able to use this guide fairly easily, so if you have any trouble, don't feel afraid to look something up.


## Web Browser
This is the most important part of privatizing your life.
If you pick the wrong browser, everything else is pretty much useless.
So choose wisely.
DON'T USE:
* Chrome/Plain Chromium
* Opera/GX
* Edge
* Firefox
* Safari

Those are the main 5 that track you.

Some safer alternatives are:
* Brave Browser (it still tracks you but it's better than others)
* [Helium](https://helium.computer/). This is the option I would recommend most people.

But the MOST secure browser, with reasonable convenience is Ungoogled Chromium.

This is regular Chromium, which is FOSS, but it removes every feature that uses Google in any way.
The only downside is some features don't work out of the box.

If you want to install browser extensions, you have to install a .crx called Chromium Web Store.

The Ungoogled Chromium team has a very good guide on this, so once you install Ungoogled Chromium, go to `chrome://ungoogled-first-run`
This guide will also help you setup spellcheck, if that's your thing.

If you also want total privacy while browsing websites, the most secure browser out of all of them is:
Tor Browser.

It routes your internet traffic through a network of relays, so your data is always secure, and even your ISP can't track you.
With other secure browsers, the main shell is secure, but it can't protect your browser traffic.

I would not recommend Tor for daily use however, because it is INCREDIBLY slow, and many sites prevent you from using them because they think you are a bot.
If you use Tor as a daily driver, get prepared for a TON of Captchas.

TLDR:
Use [Helium](https://helium.computer/) or [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium).
For more secure browsing, like _YARYARYARHARHARHAR_, use [Tor Browser](https://www.torproject.org/download/).

To install any of the search engines, look up the name of your browser, "install", and the platform you're on.

I'll leave this section off with an [article](https://discuss.privacyguides.net/t/browser-connected-domains-telemetry-test-2025-by-sizeofcat/26866) of how much each browser tracks you.
The original article is by sizeof.cat, but he archived his website.


## Searching the Web

Using a secure browser is one thing, but a search engine is an entirely different basket.
Here's how to search the web, safely, and securely.

I REPEAT, DO NOT USE:
* GOOGLE
* BING
* ECOSIA
* YAHOO
* YANDEX
* OR ANY OF THE MAJOR SEARCH ENGINES!

DuckDuckGo is fine,
Startpage is fine,
and Brave Search is fine.

But, the best option in general is a metasearch engine called
SearXNG.

The way it works, is it scrapes results from all the major search engines anonymously, and outputs them so you can get an "all in one" experience.

To use it, you either have to find an already hosted instance online, and use their link, or host your own if you have technical knowledge.

To find public instances of SearXNG, use [this](https://searx.space) website.
My favorite instance is [OpenXNG](https://opnxng.com), which not only provides a good experience, but also redirects popular social medias to the anonymous mirrors that don't track you, or put telemetry.

To host your own SearXNG, here's a good [article](https://www.bitdoze.com/searxng-self-host-privacy-search/).

Here's an [article](https://www.wikihow.com/Change-Your-Browser%27s-Default-Search-Engine) that shows you how to set your default search engine.

However, there are downsides with SearXNG.

For starters, instances occasionally take a while to load results, as they are scraped. (2-3 seconds usually, 10+ occasionally)

Because the instances use bots that scrape the results, and the corporations don't like this because it's killing their business model, they sometimes stop the bots with Captchas, or ratelimit/timeout them.

This means that sometimes, your favorite instance won't load results the first time, so you will either have to reload the page, clear your cookies, or if either of those don't work, switch instances.

For most people however, I wouldn't use SearXNG.

I would personally use DuckDuckGo, Startpage, or Brave Search.

If you really care about privacy, and don't mind inconvenience, use SearXNG.

## Extensions

For every browser, you NEED at least these 5 extensions.
To install these, go to the Chrome Web Store, or if you are using Firefox (YOU SHOULDN'T), you should go onto Firefox Addons.

* UBlock Origin/UBlock Origin Lite (preferably not lite version)
* Canvas Blocker
* Privacy Badger
* I still don't care about cookies
* Decentraleyes

These 5 extensions block ads, trackers, cookie popups, exterior cdn requests, and fingerprinting tactics, ensuring you have a saf*er* browsing experience.
