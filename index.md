---

title: Le Blog de Mohamed Maïza, un intégrateur comme un autre.
description: Ici, de tout et de rien ...
url: "https://hedimaiza.github.io/jekyll"
baseurl: ""
---

# Bonjour
{{site.description}} : coco.

<h1>{{ page.title }}</h1>
url : {{ page.url }}

<p>Lorem bla bla ipsum dolor met siniusla ipsum dolor met siniusla ipsum dolor met siniusla ipsum dolor met sinius </p>


<ul>
{% for page in site.html_pages %}
<li><a href="{{ page.url }}">{{page.title}}</a></li>
{% endfor %}
</ul>
