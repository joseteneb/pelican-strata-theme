Strata theme for Pelican
========================

This is [Pelican](http://getpelican.com/) theme based on [Strata by HTML5 UP](http://html5up.net/). You can see it live at my [blog](http://joseteneb.com)

![Screenshot](https://raw.githubusercontent.com/joseteneb/pelican-strata-theme/master/screenshot.png)

Installation
------------

Just clone this repo, then edit your "pelicanconf.py" and modify the "THEME" variable to make it point to the repo location. 


Settings
--------
The following variables can be set in your "pelicanconf.py" file in order to customize your website.


```
AUTHOR = u'xxx'
SITENAME = u"xxx"
SITESUBTITLE = 'xxx'

FAVICON = SITEURL + '/images/xxx.ico'

GOOGLE_ANALYTICS = ''

PROFILE_IMAGE = 'xxx.jpg'

DISQUS_SITENAME = ''

EMAIL = 'xxx@xxx.xx'

SOCIAL = (('twitter', 'http://twitter.com/xxx'),
          ('linkedin', 'http://www.linkedin.com/in/xxx'),
          ('github', 'http://github.com/xxx'))

MENUITEMS = (( 'Blog', 'blog.html'),
	     ( 'About', 'about.html')
	    )
```

Features
--------
* Responsive
* Integration with Disqus
* Integration with Google Analytics
* Custom menu items
* Translation menu (You can use this functionality with [I18N Sub-sites Plugin](https://github.com/getpelican/pelican-plugins/tree/master/i18n_subsites) and use a [jinja filter](https://github.com/getpelican/pelican-plugins/blob/master/i18n_subsites/implementing_language_buttons.rst) to translate the language codes)


Licence
-------

"Strata by HTML5 UP"
html5up.net | @n33co
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A simple, minimalist template that actually began life as an unused redesign of n33.co
(my personal site). Includes a (configurable) parallax background effect, Poptrox-powered
lightbox gallery, a bunch of pre-styled elements, and Sass sources for the Sass-inclined.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = Not included)

Feedback, bug reports, and comments are not only welcome, but strongly encouraged :)

AJ
n33.co @n33co dribbble.com/n33

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		CSS3 Pie (css3pie.com)
		background-size polyfill (github.com/louisremi)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
