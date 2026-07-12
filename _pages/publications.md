---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->

<!---
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->

## Journal Articles
1. Aproximating average bounded-angle minimum spanning trees  
A. Biniaz, P. Bose, and P. Devaney  
*Computational Geometry*, vol. 128, 2025  
(A preliminary version appeared in *CCCG'22*)  
[pdf](/files/papers/2025-approximating-average-bounded-angle-msts.pdf) | [doi](https://doi.org/10.1016/j.comgeo.2025.102172)

## Thesis
- Aproximating average bounded-angle minimum spanning trees  
P. Devaney  
MSc thesis, School of Computer Science, *University of Windsor*, 2023  
[pdf](/files/papers/msc-thesis.pdf)
