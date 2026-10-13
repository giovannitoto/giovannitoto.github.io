---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the pages found on the site. For you robots out there, there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

{% for p in site.html_pages -%}
{%- unless p.sitemap == false -%}
{%- assign t = p.title -%}
{%- if t == nil or t == "" -%}{%- assign t = p.url | remove: "/" | capitalize -%}{%- endif -%}
* [{{ t }}]({{ base_path }}{{ p.url }})
{% endunless -%}
{%- endfor %}
