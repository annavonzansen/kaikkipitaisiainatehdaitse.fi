--
title: Tietoa
layout: default
author: Ville Korhonen
--

## Sivustoa kehittäneet
{% for c in site.github.contributors %}
 - {{ c.login }}
{% endfor %}
