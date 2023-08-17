---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## We're a Game Dev Club!

Here's a fun blurb about us! Woah we do all kinds of stuff

## In A Fancy and Formal Way Of Speaking:

DevLUp FSU is a non-profit organization dedicated to programming and the arts as it applies to real-time graphics and Video Game development. We aim to educate and provide resources to interested FSU students, from hobbyists to professionals. We encourage respect for others as well as the values of ethical game development and design.

Our current board is:

**President:** Alec Tremblay

**Vice President:** Dion Tryban

**Treasurer:** Skylar Scorca

**Secretary:** Michael Ridgeway

**Promoting Chair:** Chris Swezy

</div>
