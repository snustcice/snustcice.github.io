---
layout: default
---

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

<!--Reference : https://jekyllrb.com/docs/posts/#categories-and-tags -->
<!--Reference : https://shopify.github.io/liquid/filters/newline_to_br/ -->
<!--Reference : https://heliumdev.com/blog/create-an-array-in-shopifys-liquid -->