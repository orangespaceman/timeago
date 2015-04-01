timeago
=======

Turn absolute dates into relative time

Uses a single 'global' setTimeout call once a second, rather than a separate setInterval for every element

Init
----
To start, call ```timeAgo.init();```


Adding Dates
---
To add a relative date, call ```timeAgo.add($el);``` where ```$el``` is a jQuery object containing the element


HTML
---
Can be used with HTML element, but it must have a data attribute of ```datetime``` which is correctly ISO8601 formatted, e.g. ```2013-04-27 22:58:43``` - this can be generated easily with JavaScript or a server-side language


Requirements
---
Just import jQuery, and then the timeAgo script


Credits
---
Inspired by [Smart Time Ago](http://pragmaticly.github.io/smart-time-ago/) and [timeago](http://timeago.yarp.com)
