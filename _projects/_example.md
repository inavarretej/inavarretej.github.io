---
layout: page
title: project title
description: short description shown on the card
img: assets/img/your-image.jpg # optional thumbnail
importance: 1 # order within category (lower = first)
category: work # groups projects; use same string to group
related_publications: true # set to true to show related bib entries
---

Project description goes here. Supports standard markdown and Liquid.

# Adding images

{% raw %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/your-image.jpg" title="caption" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
{% endraw %}
