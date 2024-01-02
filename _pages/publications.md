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

---

**Open-Set Object Detection By Aligning Known Class Representations**

*Published in WACV 2024 **(Oral)***

**Hiran Sarkar**, Vishal Chudasama, Naoyuki Onoe, Pankaj Wasnik, Vineet Balasubramanian

[[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Sarkar_Open-Set_Object_Detection_by_Aligning_Known_Class_Representations_WACV_2024_paper.pdf)]

---

**Subsidiary Prototype Alignment for Universal Domain Adaptation**

*Published in NeurIPS 2022*

Jogendra Nath Kundu\*, Suvaansh Bhambri\*, Akshay Ravindra Kulkarni\*, **Hiran Sarkar**, Varun Jampani, Venkatesh Babu Radhakrishnan

[[Paper](https://arxiv.org/abs/2210.15909)]

---

**Concurrent Subsidiary Supervision for Unsupervised Source-Free Domain Adaptation**

*Published in ECCV 2022*

Jogendra Nath Kundu\*, Suvaansh Bhambri\*, Akshay Ravindra Kulkarni\*, **Hiran Sarkar**, Varun Jampani, Venkatesh Babu Radhakrishnan

[[Paper](https://arxiv.org/abs/2207.13247)]

---
