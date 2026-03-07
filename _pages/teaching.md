---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

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
<a href="{{ base_path }}{{ post.url }}"><strong>{{ post.title }}</strong></a>
({{ post.type }}{% if post.venue %}, {{ post.venue }}{% endif %}{% if post.date %}, {{ post.date | date: "%Y" }}{% endif %})
</li>

{% endfor %}

</ul>