---
title: Parcerias
modified: 2017-12-26T00:00:00.000Z
excerpt: As nossas parcerias tornam-nos mais fortes. Conhece os nossos parceiros!
share: false
edit: false
---
Se a tua associação tem valores e objetivos semelhantes a nós, então uma parceria seria vantajosa para ambos! Apresenta-te num [email](contact@portugal.beta-europe.org) e entraremos em contacto assim que possível.

Estamos abertos a novas parcerias e dispostos a colaborar contigo!

{% include map.html geojson="/partners.geojson" %}
{% include base_path %}
<div class="grid__wrapper grid__partners">
{% for post in site.partners %}
{% include archive-single.html type="grid" %}
{% endfor %}
</div>
