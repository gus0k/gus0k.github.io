---
layout: prices
title: El precio de ser vegano en Montevideo
author: Diego Kiedanski
tag: vegan, veganism, montevideo, uruguay, money
---

## List of products

<ul>
{% for item_hash in site.data.veg_prices_mvd %}
{% assign item = item_hash[1] %}
  <li>
    <a>
      {{ item.name }}
    </a>
  </li>
{% endfor %}
</ul>
