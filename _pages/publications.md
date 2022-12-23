---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

***

[Subsidiary Prototype Alignment for Universal Domain Adaptation](https://arxiv.org/abs/2210.15909)

*Published in NeurIPS 2022*

Jogendra Nath Kundu*, Suvaansh Bhambri*, Akshay Ravindra Kulkarni*, **Hiran Sarkar**, Varun Jampani, Venkatesh Babu Radhakrishnan

***

[Concurrent Subsidiary Supervision for Unsupervised Source-Free Domain Adaptation](https://arxiv.org/abs/2207.13247)

*Published in ECCV 2022*

Jogendra Nath Kundu*, Suvaansh Bhambri*, Akshay Ravindra Kulkarni*, **Hiran Sarkar**, Varun Jampani, Venkatesh Babu Radhakrishnan

***
