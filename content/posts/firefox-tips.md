---
title: "Firefox for Power Users"
date: 2021-10-08T20:16:51-07:00
author: 'chris'
draft: false
---

## Here are a few tips/tricks/hacks to make a power user feel at home inside Mozilla's Firefox.

I have been using Firefox as my daily driver browser for about 3 years now, when I decided to finally give Chrome the boot it was due to it munching all my machine's RAM, but if I had known how many little quality of life features Firefox had in store for me, I would have switched much sooner. After a few years of configuring, tweaking and experimenting with it, I have turned my Firefox install into a tool that fits in with my terminal-centric, hands-always-on-keyboard workflow. 


  

### 1. That's no address bar...

  

...its a space station! Star Wars quotes aside, Firefox's address bar is way more powerful than most people think. Think of it more like the command palate from VSCode or Sublime, it offers a wide variety of cool stuff with a few key presses. The most powerful trick I use here is context-aware search. Context-aware search is absolutely brilliant! You have a website in your bookmarks that you want to quickly navigate to without touching your mouse or scrolling through a million options on your search history? I do, like 300 times a day. What do the non-power users do? They pull up their bookmarks or click on the item in their bookmarks bar...does it work? Yeah, sure but its slow and it requires me to touch my mouse, which I consider affront to all geeks who have come before me. 

The following key combination will now be your new favorite thing on planet earth: 

 - Ctrl + L - To jump to your address bar if Firefox is your active window
 - \* - to indicate you want to search your bookmarks 
 - The first few characters of the site you want

<screenshot>

Want to search history? No problem substitute your * for a ^ and you are good to go!

Keep in mind, this doesn't just search the URL, but the page's title, you want to find that youtube video you were watching about chicken but you don't remember exactly when you saw it or what channel it was on? ^chicken will get you what you want:

<screenshot>

Same works for your open tabs, just use % to search those too. 

You can also use your address bar to search certain websites, for example if you want to search amazon for speakers, you don't need to load up amazon's landing page, just enter @amazon in your search bar followed by your search term. Same goes for duck duck go via the @ddg shortcut and wikipedia via @wikipedia (you can shorten this to @wiki in your Search Shortcuts Settings)

Finally, if the built-in options dont have what you want, you can always install additional search providers via [Mozilla's add-on page](https://addons.mozilla.org/en-US/firefox/extensions/category/search-tools/) 

### 2. Stop scrolling with the scroll wheel!

I have a mouse, its a good mouse, I like it a lot. That being said, I want to use it as little as possible. Removing my fingers from the home row takes time and I don't like doing it. Can you navigate a page in Firefox via the arrow keys? Yeah, but your arrow keys (depending on your keyboard) are not where your fingers naturally rest, your finger should be sitting at ASDF and JKL; respectively. Vim users will argue that your right hand should be at home on HJKL, which I don't really understand but sure, if hardcore Vim is your religion, be my guest (I remap these in Vim to JKL; myself, it makes way more sense and ***yes***, this is a hill I am willing to die on).  Allow me to present to you my first-installed Firefox add-on; [Vim Vixen](https://addons.mozilla.org/en-US/firefox/addon/vim-vixen/) 

Vim Vixen is pretty simple, it adds a few Vim keybinds to your standard page navigation, good ole Vim favorites like gg to go to the top of a page and G to go to the bottom. which is neat but most importantly it lets use J and K to scroll up and down. You can also use Vim Vixen to do some crazy text-based navigation as shown on their add-on page, but that is a little beyond what I use it for. 


### 3. Switch Tabs on the fly

This one is short and sweet. Ctrl + Tab cycles through your active tabs, easy as that. This paired with a good application switcher/launcher (My vote is always for Pop_OS' flavor, [shown here](https://youtu.be/aqj0cRTZaVE?t=9), but pick your own poison) can really speed up your workflow, I'm not talking a "save-you-hours-per-day" type speed increase but a few seconds here and there really adds up over a work week. 

### 4. Themes that don't suck

Let's be really honest here, default Firefox is not pretty...I mean it isn't as bad as some browsers but it ain't no looker neither. Firefox is pretty customizable and offers you a few themes to start out with out-of-the-box. The prepackaged themes are also ugly as sin... So, what can we do to make our install of Firefox [UnixPorn](https://www.reddit.com/r/unixporn/) worthy? We go with one of the tried and true themes that you see on there all the time, here are a few of my favorites but there are a lot of good ones out there if you are willing to wade through the bad eggs:

[Dracula](https://addons.mozilla.org/en-US/firefox/addon/dracula-dark/) - This is my current daily driver, the Dracula theme is available for almost any piece of software that accepts theming, VSCode, Datagrip, Slack, GTK...you name it, it probably has a Dracula theme available for it, but if you aren't sure you can always check the [official website](https://draculatheme.com/).

[Arc Dark](https://addons.mozilla.org/en-US/firefox/addon/arc-dark-theme-we/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) - This one is clean and simple, blacks and grays.

[Rainbow Blur](https://addons.mozilla.org/en-US/firefox/addon/rainbow-blur-1/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) - If you want a bit more color, this one is for you. 

And of course, if you can't find anything quite to your taste and you have some free time on your hands, [feel free to build your own.](https://extensionworkshop.com/documentation/themes/)


### 5. New Tabs to lower your blood pressure

Now that you have the power of the address bar under your belt, you really don't need Firefox's default new tab screen to display your recently visited sites, right? So, lets reclaim some of that space you just freed up! Meet [Tabliss](https://addons.mozilla.org/en-US/firefox/addon/tabliss/), a less evil and in my opinion, vastly better version of the now paid?!?!?! new tab add-on, Momentum. Tabliss does one thing and does it well, it gives you a random pretty image when you fire off a new tab, that's it. You can also have it tell you the time, weather or have it give you a inspiring quote if that's your thing...I just like the pretty pictures. This add-on is better than Momentum for three reasons: 

 1. Minimal permissions - Why does Momentum need to see my browser history?!?!
 2. Its free - WHO THE HELL IS GOING TO PAY A MONTHLY FEE FOR THIS?!?!?
 3. Its customizable - You can drop your own CSS in to style it, its not as good as writing your own new tab page (and there will be a post about that at some point) but for quick and easy, it does the job. 

### Bonus: Web apps that make life easier

In addition to pimping your browser-ride, there are a few simple web applications that I have stashed in my bookmarks bar that really up my productivity, they might help you out if your workflow is anything like mine:

- [StackEdit](https://stackedit.io/) - This is online Markdown editor, vastly superior to VSCode's. I have no idea why anyone would use anything else. It's fast, has a clean UI and does things like exports to HTML if you need it to. No more writing ugly Readme.MDs for me!
- [RegEx101](https://regex101.com/) - The best way I can describe this one is a RegEx IDE or maybe RegEx REPL? It makes this mysterious and infuriating part of my job just a little less so. I would love someone to bundle this, or something like it,  into a VSCode Extension but until then, this does the trick.
- [XML Beautifier](https://codebeautify.org/xml-pretty-print) - I spend a lot of time working with APIs, its just a part of the job. Fortunately for me, VSCode has a pretty decent JSON pretty-print extension that can turn unformatted JSON into something fairly readable...the same cannot be said for XML. I work in the medical industry, which is about 4-5 years behind technology-wise and man, these guys love SOAP, which means they really love XML, like....a lot. So what do you do when a random integration component spits out a log full of nonsense unformatted XML, you dump it into this web app to make it readable!


