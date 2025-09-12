---
title: Projects
nav:
  order: 2
  tooltip: Software, website and resources.
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects


{% include tags.html tags="software, website, resources" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
