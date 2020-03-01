---
title: "Simulação de Política Europeia"
layout: splash
permalink: /
date: 2017-04-11 01:48:41 -04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/meul-2018.jpg
  _cta_label: "Join Our Network"
  _cta_url: "http://forum.beta-europe.org"
  caption: "Photo credit: [**MEU Lisbon 2018**](https://www.facebook.com/MEULisbon/)"
excerpt: |
  A Bringing Europeans Together Association Portugal (BETA Portugal) é uma associação juvenil sem fins lucrativos que pretende promover o conhecimento sobre as instituições europeias e sobre o que significa ser cidadão europeu.

intro_01:
  - title: Quem somos?
    image_path: /assets/images/beta-logo-600.png
    alt: "BETA Logo"
    excerpt:
    |
      A BETA Portugal é composta por um grupo de jovens dinâmicos de todo o país, fundada em 2017.
    url: "/about/"
    btn_label: "Conhece a nossa equipa"
    btn_class: "btn--primary"

---

{% include feature_row id="intro_01" type="left" %}

A nossa missão é contribuir para o desenvolvimento de uma consciência europeia na juventude de toda a Europa e sensibilizar a população sobre como a União Europeia funciona e o que significa fazer parte desta organização.

[Sobre nós](/about/){:.btn .btn--primary}

De modo a atingirmos os nossos objetivos, iremos realizar diversos eventos por todo o país, sendo o principal o Model European Union Lisbon.

[Eventos](/events/){:.btn .btn--primary}

<div class="layout--splash__recent--posts">
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
</div>
