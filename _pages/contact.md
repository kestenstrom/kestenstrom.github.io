---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
---

You can contact me at:

kestenstrom [at] neiu [dot] edu


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
