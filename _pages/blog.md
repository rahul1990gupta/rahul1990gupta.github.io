---
title:  "Blog"
layout: archive
permalink: /Blog/
author_profile: true
comments: True
---
I have been writing my thoughts on various topics in the form of blog posts. Hope you enjoy it!


<ul>
  {% for post in site.posts %}
   {% include archive-single.html %}
  {% endfor %}
</ul>
