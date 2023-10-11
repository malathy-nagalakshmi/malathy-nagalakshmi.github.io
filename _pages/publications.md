---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

{% for post in site.publications reversed %}
    {% if post.type == 'conference' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}

<h1>Posters</h1>

{% for post in site.publications reversed %}
    {% if post.type == 'poster' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}

<h1>Preprints</h1>

{% for post in site.publications reversed %}
    {% if post.type == 'preprint' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}



