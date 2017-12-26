---
title: Parcerias/ Partners
modified: 2017-12-26T00:00:00+00:00
excerpt: As nossas parcerias tornam-nos mais fortes. Conhece os nossos parceiros!
---

The network of BETA Europe is strong thanks to its partners.

{% include map.html geojson="/partners.geojson" %}

{% include base_path %}

<div class="grid__wrapper grid__partners">
  {% for post in site.partners %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
