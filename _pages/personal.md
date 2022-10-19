---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true

---

{% include base_path %}

{% if post.header.teaser %}
  {% capture teaser %}{{ post.header.teaser }}{% endcapture %}
{% else %}
  {% assign teaser = site.teaser %}
{% endif %}


Hobbies
-----
In my free time, I like traveling, skiing, diving, and making all kinds of things by hand. Here are some of my works.   

### Paper model of miku

<div align="center">    
    <img src=
      {% if teaser contains "://" %}
        "{{ teaser }}"
      {% else %}
        "{{ teaser | prepend: "/images/miku1.jpg" }}"
      {% endif %}
      width=400> 
    <img src="/images/miku2.jpg" width=400>
    <img src="/images/miku3.jpg" width=400> 
    <img src="/images/miku4.jpg" width=400>
    <img src="/images/miku5.jpg" width=400> 
    <img src="/images/miku6.jpg" width=400>
    <img src="/images/miku7.jpg" width=400> 
    <img src="/images/miku8.jpg" width=400>
</div>


### Pottery

<div align="center">    
    <img src="/images/pottery.jpg" height=500> 
</div>


### Traditional Chinese fine-brush flower-and-bird painting

<div align="center">    
    <img src="/images/painting.jpg" width=400> 
</div>


### Hu Tao in Game Genshin Impact

<iframe height=400 src="/images/hutao.mp4">
</iframe>

  
### LEGO (Friends)

<div align="center">    
    <img src="/images/friends1.jpg"  height=350> <img src="/images/friends2.jpg" height=350> 
</div>
