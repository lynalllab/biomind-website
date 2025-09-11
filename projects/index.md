---
title: Projects
nav:
  order: 2
  tooltip: Books, projects, software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

<!-- COULD ADD TEXT -->

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

{% include list.html component="card" data="projects" %}

# CUT BELOW

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
