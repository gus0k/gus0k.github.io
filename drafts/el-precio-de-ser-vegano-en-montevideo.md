---
layout: post
title: El precio de ser vegano en Montevideo
author: Diego Kiedanski
tag: vegan, veganism, montevideo, uruguay, money
---

# This is a test

## List of products


{% raw %}
<ul>
{% for item_hash in site.data.veg_prices_mvd %}
{% assign item = item_hash[1] %}
  <li>
    {{ item.name }}
  </li>
{% endfor %}
</ul>
{% endraw %}
