---
layout: archive
permalink: /
title: "Welcome!"
---

I am a reader.  As my family and friends know, when I am reading about a certain topic, I am always throwing out little interesting bits of trivia that I run across.  I will spare them, and collect all these little pieces here.  

Right now I am reading about the cities I will visit in May as part of a trip I am taking with my daughter.  I will be accompanying 14 high school kids and three adults for 10 days in Europe.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
