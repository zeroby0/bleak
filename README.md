# Bleak

An elegant AJAX driven theme for [Ghost](http://github.com/tryghost/ghost/).
Originally developed by [Peter Amende](http://zutrinken.com/), I'm modifiying it to suit my needs and add some features.

### Original read-me from here
***

_**Hint:** This theme works with AJAX, so it won’t work with multiple domains properly! Use redirects to only one domain instead. Also make sure you haven’t jQuery injected in your footer due to [Ghosts migration method](http://dev.ghost.org/no-more-jquery/). This can break the layout!_

## Demo

* [Blog](http://bleak.zutrinken.com)
* [Post](http://bleak.zutrinken.com/demo)
* [Tags](http://bleak.zutrinken.com/tag/general)
* [Author](http://bleak.zutrinken.com/author/zutrinken)

## Features

* Responsive layout
* Contact Form
* Blog navigation
* Post navigation
* Cover images for blog, tag and author archives
* Featured posts style
* Automatic code syntax highlight and line numbers
* Disqus support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus="YOUR_DISQUS_SHORTNAME";</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli
	
Install Grunt modules:

	npm install

Install [Bower](http://bower.io):

	npm install -g bower

Install Bower components:

	bower install

Build Grunt project:

	grunt

Distribute Grunt project:

	grunt build

## Contact Form

edit `page-contact.hbs`, change `url: "https://formspree.io/zerodividedby0@gmail.com"` to `url: "https://formspree.io/your-email@example.com"`  
The first time you submit through this form, formspree sends you a verification email, verify clicking the link, and you'll receive and email  
when ever someone submits through your form.

To create a page for contact form in your Ghost blog, create a new post with title 'Contact' and mark it as a static page. Make sure that the url  
to the page is `yourblog.com/contact`, you can adjust your page to have this in the navigation tab.


## Copyright & License

Copyright (C) 2015-2016 Peter Amende - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
