---
title: YouTube on 2012 Samsung Smart TV
---

I have a problem with YouTube on my Samsung Smart TV bought around 2012. It hangs ramdomly, but most usually on startup. There is no update for the YouTube app. TV firmware was upgraded to the latest version (solving nothing).

Googling for "youtube samsung smart tv" will outline that there is a [youtube.com/tv][] app for newer models. That there are [different][] app versions out there.

[youtube.com/tv]: https://support.google.com/youtube/answer/3015415?hl=en
[different]: https://support.google.com/youtube/answer/3153576?hl=en&ref_topic=1732965

YouTube Help will [tell you][] that...

[tell you]: https://support.google.com/youtube/answer/3153576?hl=en&ref_topic=1732965

> If your TV model is from 2012 or earlier, you likely have the older version of the YouTube app.

Older version of the app is a [flash][] app. Which wasn't updated since 2015, i.e. for two years already, so it could be counted as an outdated client.

[flash]: https://support.google.com/youtube/answer/3210458

No solution so far, so I continue my quest by googling for flash app filename, which is `leanbacklite_v3.swf`.

Among nonsense results, there is a link to a thread on OpenLGTV board.

> OpenLGTV is a non-commercial project for legal reverse engineering and research on LG Television firmware which is partially Open Source.

`netcast` is a key from that thread which I don't understand, so I google for "youtube netcast", which [links][] me to _YouTube App No Longer Works - Netcast - LG_.

[links]: http://www.lg.com/us/support/product-help/CT10000018-1432330562046-others

---

_LG Help Library_ is a UX disaster on its own. It prevents me from coping a text for a quote. Quite obviously it prevents context menu too:

```html
<div
  oncontextmenu="return false"
  onselectstart="return false"
  ondragstart="return false">
```

---

It is for LG, not for Samsung, but for the first time I see something helpful:

> YouTube has ended support for many devices from All manufacturers.

OK, _YouTube has ended support_. But article also mentions a solution

> [...], there are alternative methods to view YouTube on your TV, called Streaming Devices.

> <p>One of the most popular Streaming Devices is Google's <a href="https://www.google.com/chromecast/tv/explore/">Chromecast</a>, though any device that supports YouTube or <b>Casting</b> will work. CNET has a comprehensive review of the Streaming Devices available at <a href="http://www.cnet.com/news/chromecast-vs-apple-tv-vs-roku-3-which-media-streamer-should-you-buy/">http://www.cnet.com/news/chromecast-vs-apple-tv-vs-roku-3-which-media-streamer-should-you-buy/</a>.</p>

LG is the best ;) I need another smart device which would use my TV as a big dumb screen.

# How YouTube, Google or Samsung may do it better?

I assume that maintaining apps on old devices is hard, and I certainly know that distributed system with outdated components will eventually collapse. But at least marketing could be done better.

YouTube, Google or Samsung, please advertise Chromecast right away on all pages refering to "older YouTube app".

# Solution

Yes, I may buy Chromecast after reading some reviews. But given the quick aging of closed products I better prefer open systems.

It makes more sense to tinker home-made Raspberry Pi media center than buying another _soon-to-be-dumb_ smart device.
