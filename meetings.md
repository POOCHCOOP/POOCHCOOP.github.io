---
layout: default
title: Board Meetings
permalink: /meetings/
---

## Agendas & Minutes
<ul>
	{% for doc in site.agenda %}
		{% if doc.category == "meetings" %}
			<li><a href="{{ doc.url }}">{{ doc.title }}</a></li>
		{% endif %}
	{% endfor %}
</ul>
