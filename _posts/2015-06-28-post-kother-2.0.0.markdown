---
title:  "Post Köther 2.0.0"
date:   2015-06-28 08:18:00
description: Meetup Talks Hack
author: benjick
authorTwitter: benjick
---

![Bash & Bärs](/assets/images/bashbars.jpg)

So the weekend is over, I'm the only one awake this early and we've had a lot of fun. We've made one simple application (APK) and we've had three talks! @norrskal talked about bash, @wibron talked a bit about React and ES6 and I talked about Meteor.

The application we built is an "alcohol per currency" application which gives you a value on the worth of a beverage (beer, spirits, wine etc) taking only the ABV and price into consideration. All this data comes from our goverment owned liquor stores (Systembolaget) and we use a simple formula to calculate the APK value.
{% highlight javascript %}
var apk = (( alcohol / 100 ) * volume ) / price;
{% endhighlight %}

The site is in Swedish and it's available at [http://apk.kother.io/](http://apk.kother.io/)

The source code can be found at [https://github.com/dumfan/apk](https://github.com/dumfan/apk)

@wibron also built a Chrome extension to append this value to systembolaget.se, it can be downloaded at [the Chrome store](https://chrome.google.com/webstore/detail/systembolaget-apk/njcbniedjlbhdnolbchleaocgkhojofl)

Source code available at [https://github.com/dumfan/apk-chrome](https://github.com/dumfan/apk-chrome)

Cheers,  
@benjick
