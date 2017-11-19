---
layout: post
title: "Vad är Open Graph och hur använder du det?"
date: 2017-11-16 04:12:00 + 0100
comments: true
categories: jekyll update
---

Open Graph är ett massa metataggar som du väljer att importera i ett html dokument. Detta gör att när man länkar sin sida kommer ett fält med utvald information fram såsom bild, en textsträng och så vidare. Detta var från början skapat av Facebook.

Jag valde att använda Open Graph genom att min bakgrundsbild från min webb-sida syns, mitt för- och efternamn och även en beskrivning av vad sidan är skapad för.



{% highlight ruby %}
<title>Marcus Wallin</title>
<meta property="og:title" content="Marcus Wallin" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://mackanw3.github.io" />
<meta property="og:image" content="https://mackanw3.github.io/img/dator.jpg" />
<meta property="og:description" content="Denna hemsida är skapad för kursen 1Dv022 på Lnu i Kalmar" />
{% endhighlight %}