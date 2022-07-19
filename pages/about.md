---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
My current goal is to complete my education while working to gain professional experience in my field of interest.
During my university courses I learned the basics of electronics, spanning from analog to digital circuits, high and low level programming and FPGA programming using VHDL. I also had the possibility to work in groups, learning how to manage and develop bigger projects. 
I'm a good team worker, very result-driven and motivated by new challenges. I'm looking forward to traveling both nationally and internationally if my job requires it.


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html title="Professional Experience" source=site.data.timeline-work %}
</div>

<div class="row">
{% include about/timeline.html title="Education" source=site.data.timeline-education %}
</div>