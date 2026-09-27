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

I am a sixth-year Ph.D. student in Electrical and Systems Engineering at the University of Pennsylvania, advised by Prof. Jing Li, and expect to graduate in 2027. Before Penn, I received my M.Phil. from HKUST and my B.Eng. from CUHK.

My research spans computer architecture, high-performance networking, reconfigurable computing, storage systems, and hardware security. I am particularly interested in building efficient hardware and hardware–software systems for communication- and data-intensive workloads, including datacenter interconnects, FPGA-accelerated storage, and programmable architectural mechanisms.

My recent work includes R2D2, a reconfigurable network for disaggregated datacenters published at ISCA'26, and FPGA-based systems for tightly integrating computation with NVMe storage (FPGA'26, TRETS'24, FPGA'23). I am also actively working on hardware mechanisms for efficiently propagating and checking software-programmable metadata, including tagged architectures and pointer authentication.

<h2 id="publications">Publications</h2>

You can also find my articles on [Google Scholar]({{ site.author.googlescholar }}).

{% for post in site.publications reversed %}
  {% include archive-single.html homepage=true %}
{% endfor %}

<h2 id="teaching">Teaching</h2>

{% for post in site.teaching reversed %}
  {% include archive-single.html homepage=true %}
{% endfor %}
