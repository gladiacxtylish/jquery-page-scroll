jquery-page-scroll
==================

Overview
--------

A jQuery plugin to create page entity scroll effect websites. The plugin forces users to scroll one page at a time to improve user experience.

Installation
------------

To install the plugin to your website, simply include the latest jQuery library and include the code below to the `head` tag.

```html
<link rel="stylesheet" href="css/jquery.page-scroll.min.css">
<script src="js/jquery.page-scroll.min.js"></script>
```

Usage
-----

Structure the HTML `body` as the following:

```html
<div id="page-scroll-container">
  <div class="page-scroll-page">...</div>
  <div class="page-scroll-page">...</div>
  ...
</div>
```

Initialize page-scroll plugin:
```javascript
$('#page-scroll-container').pageScroll();
```

Options
-------

### animateDuration
The time duration of the animate effect in millisecond.

Issues
------

If you found a bug, [create a new issue here](https://github.com/gladiacxtylish/jquery-page-scroll/issues).

Changelogs
----------

### 1.0
The first version with the option of animateDuration released.

Author
------

[Jeffrey Chen](http://www.thejeffreychen.com)

License
-------

The MIT License (MIT)

Copyright (c) 2013 [Jeffrey Chen](http://www.thejeffreychen.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
