# Social Sharing
Add social sharing links and buttons without the bloat.

[Download Social Sharing](https://github.com/cferdinandi/social-sharing/archive/master.zip) / [View the demo](http://cferdinandi.github.io/social-sharing/)

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Browser Compatibility](#browser-compatibility)
3. [How to Contribute](#how-to-contribute)
4. [License](#license)
5. [Changelog](#changelog)



## Getting Started

### 1. Include Social Sharing on your site.

```html
<link rel="stylesheet" href="css/social-sharing-css.css">
```

If you're not using the [Kraken boilerplate](http://cferdinandi.github.io/kraken/), you might also need to include the button styling.

```html
<link rel="stylesheet" href="css/kraken-buttons.css">
```

Social Sharing is [built with Sass](http://sass-lang.com/) for easy customization. If you don't use Sass, that's ok. The `css` folder contains compiled vanilla CSS.

The `_config.scss` and `_mixins.scss` files are the same ones used in [Kraken](http://cferdinandi.github.io/kraken/), so you can drop the `_social-sharing.css` file right into Kraken without making any updates. Or, adjust the variables to suit your own project.

### 2. Add the markup to your HTML.

**Branded Buttons**

A few simple classes turn `button` and `a` elements into branded social media buttons.

```html
<a class="btn btn-tweet" href="#">Twitter</a>
<a class="btn btn-facebook" href="#">Facebook</a>
<a class="btn btn-google" href="#">Google+</a>
<a class="btn btn-linkedin" href="#">LinkedIn</a>
<a class="btn btn-pinterest" href="#">Pinterest</a>
<a class="btn btn-github" href="#">GitHub</a>
<a class="btn btn-vk" href="#">VK</a>
<a class="btn btn-xing" href="#">Xing</a>
<a class="btn btn-tumblr" href="#">Tumblr</a>
```

**Sharing Links**

To include sharing links for Twitter, Facebook, Google+, LinkedIn and more, just add your URL's and titles where indicated in these snippets. Combine with the branded buttons for sharing buttons.

```html
<a target="_blank" href="https://twitter.com/intent/tweet?text=YOUR-TITLE&url=YOUR-URL&via=TWITTER-HANDLE">Tweet</a>

<a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=YOUR-URL">Share on Facebook</a>

<a target="_blank" href="https://plus.google.com/share?url=YOUR-URL">Plus on Google+</a>

<a target="_blank" href="https://www.linkedin.com/shareArticle?mini=true&url=YOUR-URL&title=YOUR-TITLE&summary=YOUR-SUMMARY&source=YOUR-URL">Share on LinkedIn</a>

<a target="_blank" href="https://pinterest.com/pin/create/button/?url=YOUR-URL&description=YOUR-DESCRIPTION&media=YOUR-IMAGE-SRC">Pin on Pinterest</a>

<a target="_blank" href="https://vk.com/share.php?url=YOUR-URL&title=YOUR-TITLE&description=YOUR-DESCRIPTION&image=YOUR-IMAGE-SRC&noparse=true">Share on VK</a>

<a target="_blank" href="https://www.xing-share.com/app/user?op=share;sc_p=xing-share;url=YOUR-URL">Share on Xing</a>

<a target="_blank" href="http://www.tumblr.com/share">Share on Tumblr</a>
```

And that's it, you're done. Nice work!



## Browser Compatibility

Social Sharing works in all modern browsers, and IE 6 and above.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Don't forget to update the version number, the changelog (in the `readme.md` file), and when applicable, the documentation.



## License

Social Sharing is licensed under the [MIT License](http://gomakethings.com/mit/).



## Changelog

* v1.4 - January 13, 2014
	* Added Tumblr support.
* v1.3 - December 6, 2013
	* Added Sass support.
* v1.2 - November 9, 2013
	* Added GitHub button.
* v1.1 - October 26, 2013
	* Added Pinterest support.
* v1.0 - June 7, 2013
	* Switched to MIT license.
* Version 1.0 - April 2, 2013
	* Initial release.