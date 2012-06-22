---
layout: page
title: Welcome
tagline: Supporting tagline
---
{% include JB/setup %}



> *“Knowing others is intelligence; knowing yourself is true wisdom. Mastering others is strength; mastering yourself is true power.”*  

>**道德经 Tao Te Ching**


#**Recent Posts:**#

<ul class="posts">
  {% for post in site.posts %}
	{% unless post.draft %}
    	<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endunless %}
  {% endfor %}
</ul>

[More](blog/pages/archive.html)
