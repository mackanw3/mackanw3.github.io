---
layout: post
title: "What is Open Graph and how do you make use of it?"
date: 2017-11-16 04:12:00 + 0100
comments: true
categories: jekyll update
---

Open Graph är ett ett gäng meta taggar som väljer att implementera i ett html dokument som gör att när man länkar sin sida kommer ett fält med utvald information fram så som bild, en text sträng och så vidare. Detta var från början skapat av Facebook.

Jag valde att implementera Open Graph genom att min bakgrunds bild från min hemsida, mitt för och efternamn och även en beskriving av vad sidan innehåller.

{% highlight ruby %}
<title>Marcus Wallin</title>
<meta property="og:title" content="Marcus Wallin" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://mackanw3.github.io" />
<meta property="og:image" content="https://mackanw3.github.io/img/dator.jpg" />
<meta property="og:description" content="Denna hemsida är skapad för kursen 1Dv022 på Lnu i Kalmar" />
{% endhighlight %}