---
layout: page
title: events
permalink: /events/
---

<p>Here is a list of our upcoming events. :-)</p>

{% if site.events %}
<ul>
{% for event in site.events reversed %}
    <li>
        <p><a href="{{ event.url }}">{{ event.title }}</a></p>
    </li>
{% endfor %}
</ul>
{% endif %}