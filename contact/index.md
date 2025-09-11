---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="l.bravo2@newcastle.ac.uk"
  link="l.bravo2@newcastle.ac.uk"
%}
{%
  include button.html
  type="phone"
  text="‪+44 7774 532356‬"
  link="‪+44 7774 532356‬"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/SdR2qivxq4Wy7zBK9?g_st=ipc"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/dove marine laboratory.webp"
  caption="Dove Marine Laboratory, Newcastle upon Tyne, United Kingdom"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/facultad de ciencias del mar y recursos naturales.webp"
  caption="Faculty of Marine Sciences and Natural Resources, Valparaiso, Chile "
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
