---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /publication
---



Visual Goal-Step Inference using wikiHow, presented at the [2nd Workshop on Advances in Language and Vision Research](https://alvr-workshop.github.io/) at [NAACL 2021](https://2021.naacl.org/) \[[pdf](https://aclanthology.org/2020.emnlp-main.374)\] \[[code](https://github.com/zharry29/wikihow-goal-step)\]
<font size="3"> Yue Yang, Artemis Panagopoulou, Qing Lyu, Li Zhang, Mark Yatskar and Chris Callison-Burch </font>

Goal-Oriented Script Construction, to appear in [INLG 2021](https://inlg2021.github.io/) \[[pdf](https://arxiv.org/abs/2107.13189)\] \[[code](https://github.com/zharry29/wikihow-intent)\]
* Qing Lyu\*, Li Zhang\*, Chris Callison-Burch
* \*: Equal contribution.

Intent Detection with WikiHow, [AACL-IJCNLP 2020](http://www.aacl2020.org/) \[[pdf](https://www.aclweb.org/anthology/2020.aacl-main.35)\] \[[code](https://github.com/zharry29/wikihow-intent)\]
* Li Zhang, Qing Lyu, Chris Callison-Burch

Reasoning about Goals, Steps, and Temporal Ordering with WikiHow, [EMNLP 2020](https://2020.emnlp.org/) \[[pdf](https://aclanthology.org/2020.emnlp-main.374)\] \[[code](https://github.com/zharry29/wikihow-goal-step)\]
* Li Zhang\*, Qing Lyu\*, Chris Callison-Burch
* \*: Equal contribution.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
