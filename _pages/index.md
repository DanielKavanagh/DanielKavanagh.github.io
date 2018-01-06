---
layout: defaults/page
permalink: /
narrow: true
---

### Recent Blog Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


