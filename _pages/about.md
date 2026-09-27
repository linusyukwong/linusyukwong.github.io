---
layout: archive
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div id="about"></div>

I am a sixth-year ESE PhD student at [UPenn](https://www.ese.upenn.edu), advised by Prof. Jing Li. Before Penn, I completed my Masters at [HKUST](https://hkust.edu.hk) and my undergrad at [CUHK](https://www.cuhk.edu.hk).

My research interests are in the intersection of hardware security, high-performance networking, storage, and accelerators. I am currently working on optimized hardware for propagating and checking software-programmable metadata (e.g. Tagged Architectures and Pointer Authentication).

<h2 id="publications">Publications</h2>

You can also find my articles on [Google Scholar]({{ site.author.googlescholar }}).

{% for post in site.publications reversed %}
  {% include archive-single.html homepage=true %}
{% endfor %}

<h2 id="teaching">Teaching</h2>

{% for post in site.teaching reversed %}
  {% include archive-single.html homepage=true %}
{% endfor %}
