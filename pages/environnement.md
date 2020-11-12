---
layout: page
title: "Environnement et Couthenans"
subheadline: ""
teaser: "L'environnement est un point important de notre équipe, voici l'ensemble des actualités qui s'y rapporte"
permalink: "/environnement/"
header:
    image_fullwidth: "header_drop.jpg"
---
<ul>
{% for post in site.categories.environnement %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
