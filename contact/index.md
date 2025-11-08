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
  text="achar137@umn.edu"
  link= "achar137@umn.edu"
%}


{% include section.html dark = True %}

{% capture col1 %}

{%
  include figure.html
  image="images/Reecha_field.JPG"
  caption="Reecha"
%}

{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/2025_crkscoring.JPG"
  caption="FHB scoring 2025 at Crookston"
%}
{% endcapture %}
{% include cols.html col1=col1 col2=col2 col3=col3 %}
