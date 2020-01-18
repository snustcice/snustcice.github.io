---
layout: default
---

{% for category in site.categories %}
<h3>{{ category[0] }}</h3>
<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
	</li>
	{% endfor %}
</ul>
{% endfor %}

<!--Reference : https://shopify.github.io/liquid/filters/newline_to_br/ -->
<!--Reference : https://heliumdev.com/blog/create-an-array-in-shopifys-liquid -->
{% assign top-level-category = "Dept. of CSE, Personal Practice, Personal Project, TeamCrazyPerformance" | split: ',' %}
{% assign dept-of-cse-category = "2019-1 Introduction to Computer Engineering_ko, 2019-1 Introduction to Programming(1)_en, 2019-2 Basic Engineering Design_ko, 2019-2 Introduction to Programming(2)_en" | split: ',' %}
{% assign p-prctc-category = "Certification, Git&GitHub, Operating System, Programming Language" | split: ',' %}
{% assign crtf-category = "Computer Specialist in Spreadsheet & Database Level-1, Craftsman Information Processing" | split: ',' %}
{% assign os-category = "TIZEN" | split: ',' %}
{% assign pl-category = "C++, Python" | split: ',' %}
{% assign tcp-category = "Group Study, Project" | split: ',' %}