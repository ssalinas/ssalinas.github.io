---
layout: archive
title: "Oliver The Havanese"
date: 2015-06-27T17:02:00-00:00
modified:
excerpt: "A break from coding, let's play with the puppy!"
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.puppy %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->