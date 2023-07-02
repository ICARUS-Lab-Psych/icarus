---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Meet our lab members

We are dedicated to conducting high-quality research and translating our 
findings into clinical practice, with the ultimate goal of improving the lives 
of people affected by mental health problems.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

# {% include icon.html icon="fa-solid fa-users" %}Temporary members

{% include section.html %}

{% include list.html data="_temp.members" component="portrait" filters="role: pi" %}
{% include list.html data="_temp.members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}
