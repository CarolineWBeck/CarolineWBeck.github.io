---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Beck Lab Members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

what's this?

{% include section.html %}

{% capture content %}

{% include figure.html image="images/CB-web.jpg" %}
{% include figure.html image="images/phoebe_web.jpg" %}
{% include figure.html image="images/sulagna-web.png" %]
{% endcapture %}

{% include grid.html style="square" content=content %}
