---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}

### [{{ post.title }}]({{ base_path }}{{ post.url }}) [{{ post.type }}{% if post.venue %}, {{ post.venue }}{% endif %}{% if post.date %}, {{ post.date | date: "%Y" }}{% endif %}]

{% endfor %}