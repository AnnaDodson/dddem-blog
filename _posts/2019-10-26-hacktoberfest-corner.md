---
title: 'Hacktoberfest at DDD: East Midlands'
layout: post
description: "Hacktoberfest visits DDD: East Midlands."
date: 2019-10-24
cover: "/assets/header_image.jpg"
author: Anna Dodson and Jamie Tanna
categories: [hacktoberfest]
comments: false
share: false
---
Although the month of [Hacktoberfest](https://hacktoberfest.digitalocean.com/) is almost over, we're going to have a [Hacktoberfest stand at DDD East Midlands today](https://www.dddeastmidlands.com/hacktoberfest/).

As part of this, we're looking at making it easier to contribute while you're here, so simply raise a Pull request to add an image to the folder `assets/img/2019-10-26/hacktoberfest-corner/`, and it'll automagically get displayed below:

<section class="contributors_grid">
{% for image in site.static_files %}
{% if image.path contains 'img/2019-10-26/hacktoberfest-corner' %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="Profile picture for {{ image.path }}" />
{% endif %}
{% endfor %}
</section>

We've got a tonne of swag, and the chance to win an awesome pair of Sammy the Shark slippers:

**??**
