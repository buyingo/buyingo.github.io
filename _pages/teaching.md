---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<ul>

{% for post in site.teaching reversed %}

<li>
<a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>
<span style="color:#777;">({{ post.type }}, {{ post.venue }}, {{ post.date | date: "%Y" }})</span>
</li>

{% endfor %}

</ul>