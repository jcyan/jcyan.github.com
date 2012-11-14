---
layout: page
tagline: Supporting tagline
---
{% include JB/setup %}



> Your work is going to fill a large part of your life, and the only way to be truly satisfied is to do what you believe is great work. And the only way to do great work is to love what you do.



###**Recent Posts:**###

<ul class="posts">
  {% for post in site.posts %}
	{% unless post.draft %}
    	<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endunless %}
  {% endfor %}
</ul>

[More](blog/pages/archive.html)
