---
layout: page
title: "Environnement et Couthenans"
subheadline: ""
teaser: "La sécurité fait partie des éléments régaliens de la commune, voici l'ensemble des articles s'y rattachant"
permalink: "/sante_securite/"
header:
    image_fullwidth: "header_unsplash_12.jpg"
---
<ul>
{% for post in site.categories.securite %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
