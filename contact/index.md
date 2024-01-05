---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Caroline Beck

{%
  include button.html
  type="email"
  text="caroline.beck@otago.ac.nz"
  link="caroline.beck@otago.ac.nz"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/greeneyefrog226.jpg"
  caption="Transgenic frog with green fluorescent protein in the lens of the eye "
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="lens ISH web.jpg/photo.jpg"
  caption="In situ hybridisation of lens expressed genes in early _Xenopus_ embryos"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
#Development
{% endcapture %}

{% capture col2 %}
#Regeneration
{% endcapture %}

{% capture col3 %}
#Epilepsy
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
