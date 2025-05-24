---
layout: default
title: Blog
---

{% include hero.html title="The beekeeping blog" subtitle="What does a beekeeper actually do?" %}

One of the questions I often get asked is "how much effort does it take to keep bees?"

That's a really hard question to answer. I could talk about the time I spend over the winter making a cleaning equipment, I could talk about swarm season and how it's really important to inspect the bees at least every 7 days, I could talk about honey extraction and how long it takes to clean and sterilise all the equipment.

Instead I've decided to blog all the activities I undertake as a beekeeper. I keep records anyway (as every good beekeeper should) so I'm just going to start keeping those records here.

This is absolutely not meant to be any kind of course in how to keep bees. If you're looking for one of those then head to YouTube, there's hundreds (if not thousands) of them, even better find your local [beekeeping association](https://www.bbka.org.uk/find-beekeeping-near-you). Instead this is just ma log of what I, an hobbyist with a couple of hives in my garden, end up doing as a beekeeper.

{% for post in site.posts %}
* [ {{ post.date | date_to_string: "ordinal", "GB" }} {{ post.title }}]({{ post.url }})
{% endfor %}