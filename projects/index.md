---
title: Manish Kukreja
layout: module
---

# Modules

<ul>
{% for module in site.data.modules %}

	<li>
		<a href="{{ site.baseurl }}/{{ site.modules_dir }}/{{ module.slug }}"
		   class="">
			{{ module.name }}
		</a>
	</li>

{% endfor %}
</ul>