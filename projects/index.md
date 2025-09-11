---
title: Projects
nav:
  order: 2
  tooltip: Books, projects, software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

<!-- COULD ADD TEXT -->

<!-- ADD THIS EVENTUALLY FOR FILTERING BUTTONS {% include tags.html tags="publication, resource, website" %} -->

{% include search-info.html %}

{% include section.html %}

{% include list.html component="card" data="projects" filter="!group" %}

{% comment %} 

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

# {% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}

{% endcomment %} 
