---
title: "Nutrition and Molecular Genetic Research - Publications"
layout: gridlay
excerpt: "cancerprevention -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

（* means equal contribution. For a full list of publications, please go to [Google Scholar](https://scholar.google.com/citations?user=zHidLmYAAAAJ&hl=en&authuser=1))

<!-- ## Full List of publications -->

### 2022
{% for publi in site.data.publist %}
{% if publi.year == 2022 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### 2021
{% for publi in site.data.publist %}
{% if publi.year == 2021 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### 2020
{% for publi in site.data.publist %}
{% if publi.year == 2020 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### 2019
{% for publi in site.data.publist %}
{% if publi.year == 2019 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### 2018
{% for publi in site.data.publist %}
{% if publi.year == 2018 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### 2017
{% for publi in site.data.publist %}
{% if publi.year == 2017 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}
### Before 2016
{% for publi in site.data.publist %}
{% if publi.year < 2016 %}
    
<strong style="color:blue"><a href="{{ publi.link.url }}">{{ publi.title }}</a> </strong><br />
{{ publi.authors }} <br /> 
<em>{{ publi.link.display }}</em>
<em><a href="https://ylab.top/{{ publi.bib }}">[bib]</a></em>

{% endif %} 
{% endfor %}