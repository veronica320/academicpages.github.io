---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /publication
---

Reasoning about Goals, Steps, and Temporal Ordering with WikiHow, EMNLP 2020 \[[pdf](https://aclanthology.org/2020.emnlp-main.374)\] \[[code](https://github.com/zharry29/wikihow-goal-step)\]
  * Li Zhang\*, Qing Lyu\*, Chris Callison-Burch
  * \*: Equal contribution.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
