---
layout: default
title: Blog
---

{% assign posts = site.blog | sort: 'date' | reverse %}
{% for post in posts %}
- {{ post.date | date: '%Y/%m/%d' }} - {% if post.author %}{{ post.author }} - {% endif %}[{{ post.title }}]({{ post.url }})
{% endfor %}

---

![Animated Fireplace GIF](/img/fireplace.gif){: .center }

---

_Last updated: 17th August 2025 (Earth time)_

[Back to Top](#top)
{: .center }
