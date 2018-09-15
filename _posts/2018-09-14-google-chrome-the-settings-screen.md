---
layout: post
title: "Google Chrome: The Settings Screen"
---

[Much has been written](https://www.theverge.com/2018/1/4/16805216/google-chrome-only-sites-internet-explorer-6-web-standards) about [Google Chrome's dominance](https://thenextweb.com/dd/2017/11/28/please-build-websites-web-not-just-google-chrome/) in the browser market. As of August 2018, [2 out of 3 desktop users](http://gs.statcounter.com/browser-market-share/desktop/worldwide) choose Chrome as their window to the Web. It is a browser for the masses, which demands that it be especially accessible and easy to use.

The Chrome team is no stranger to user-friendly design. Back in 2008, it was IE that was the king of the browser world. Chrome distinguished itself, in part, with well-considered features like [the Omnibox](https://counternotions.com/2008/09/11/omnibox/). People kept trying to type their web searches into the address bar, and it isn't difficult to distinguish a URL from a collection of keywords. Why wouldn't you combine the address bar and the search box? Every other major browser has since followed suit.

This history of good design makes Chrome's Settings screen all the more disappointing. To understand why, it's important to recognize that settings are a necessary evil. If we lived in an ideal world, everyone's browser would already be perfectly configured. Since we don't, we need to ensure that when people need to change settings, they can do so as quickly as possible.

Let's take a closer look. This is how Chrome's Settings screen appears in a narrow window.

<figure>
    <p><img class="w80" align="middle" src="/assets/images/201809_chromeSettingsNarrow.png"></p>
    <figcaption style="text-align:center">We'll pretend to not notice that the Settings screen didn't get the same Material Design 2 refresh as the rest of Chrome 69.</figcaption>
</figure>

Google is a big advocate for [responsive web design](https://developers.google.com/web/fundamentals/design-and-ux/responsive/), which enables a layout to adapt to different screen/window sizes. For a narrow window, there isn't room to permanently display a navigation menu, so it makes sense for Chrome to hide it behind a [hamburger button](https://en.wikipedia.org/wiki/Hamburger_button).

<figure>
    <p><img class="w80" align="middle" src="/assets/images/201809_chromeSettingsNarrowMenu.png"></p>
</figure>

How does the Settings screen change to take advantage of a wider window?

<figure>
    <p><img class="w100" align="middle" src="/assets/images/201809_chromeSettingsWide.png"></p>
</figure>

It doesn't. This is an exceptionally poor example of responsive design. The Settings screen doesn't use the added horizontal space to provide any more utility to the user. Instead, the extra width is wasted on an excessively large left/right margin and a search bar (which looks better than a magnifying glass but doesn't save the user any clicks).

What about that navigation menu? It's still hidden behind a hamburger button, _even though the menu doesn't cover anything when it's expanded_.

<figure>
    <p><img class="w100" align="middle" src="/assets/images/201809_chromeSettingsWideMenu.png"></p>
    <figcaption style="text-align:center">*facepalm*</figcaption>
</figure>

If we were designing a settings window from scratch, we could arrive at something resembling the Chrome Settings screen in two easy steps:

1. Leave half of the available space blank.
2. Hide the only menu behind a button click.

Does this sound like a design focused on helping the user quickly find what they need?

Google could improve the Chrome Settings screen simply by making the menu persistent when the window is wide enough. The navigation menu is genuinely useful, but a menu is no good if people aren't looking at it. A permanently visible menu (when appropriate) would markedly increase the usability of the Settings screen.

A more substantial improvement would involve the use of a multi-column layout. Depending on the window width, settings could be displayed in two or even three columns, allowing more information to be onscreen at the same time. This would be truly responsive design, adapting not only the size but also the layout of the content to make the best use of screen real estate.
