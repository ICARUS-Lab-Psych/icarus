---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="email"
  link="l.mason@ucl.ac.uk"
%}
{%
  include button.html
  type="twitter"
  text="Twitter"
  link="LiamMasonPsych"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/FJk5Hr1srij51sMy5"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/russell-square-house.jpg"
  caption="Russell Square House"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/russell-square.jpg"
  caption="Russell Square"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
