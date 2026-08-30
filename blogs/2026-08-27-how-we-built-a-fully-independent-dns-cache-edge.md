---
title: "How We Built a Fully Independent DNS Cache Edge"
url: "https://blog.dnsimple.com/2026/08/building-our-fully-independent-dns-edge/"
date: "2026-08-27"
author: "jtemple"
feed_url: "https://blog.dnsimple.com/feed.xml"
---
Last month we completed a rearchitecture of our Authoritative DNS edge network , bringing the entire cache edge network onto infrastructure we operate ourselves. Before explaining why and how we made that change, it's worth understanding how the previous architecture came to be. In 2014, we were running our own anycast network across 5 points of presence, with hardware-based DDoS defense in front of it.
