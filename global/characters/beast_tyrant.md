---
layout: global
type: character
title: Beast Tyrant
class: beast_tyrant
gallery:
  name: beast_tyrant
  path: 'img/ability_cards/beast_tyrant'
  thumb: '_thumb.jpg'
levels: ['/1', '/x', '/2', '/3', '/4', '/5', '/6', '/7', '/8', '/9']
---

{% capture special %}
  <div class="card">
    <a href="{{ site.baseurl }}/assets/img/ability_cards/beast_tyrant/special/beast_tyrant_rules.jpg" data-lightbox="beast_tyrant_special">
      <img src="{{ site.baseurl }}/assets/img/ability_cards/beast_tyrant/special/beast_tyrant_rules_thumb.jpg" alt="special_rules" />
    </a>
  </div>
{% endcapture %}

{% include character.html content=special %}
