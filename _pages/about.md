---
title: "About"
excerpt: "About the author"
permalink: /about/
is_about: true
---
{% capture bio %}
There are quite a few critics online who are smart and skilled and say interesting things. This website is my attempt to join them. I made it for fun, but also to express ideas I don't see routinely expressed.

My name is Tom Bomba. I knocked around New York University's cinema studies program before I "dropped out of college to get an education." I've spent my time since producing various forms of digital media.

_{{ site.title }}_ is intentionally basic, a sorta mental note to myself not to write as if I'm submitting for publication. The site was built on an old Mac using Jekyll, Atom, and Pixelmator, while listening to KCRW Los Angeles.
{% endcapture -%}

{{ bio | smartify | markdownify }}