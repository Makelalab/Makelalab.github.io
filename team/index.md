---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are building an interdisciplinary team combining cell biology, computational biology, machine learning, and biophysics approaches to understand how the complex cellular environment affects single molecule dynamics and function.
If you are interested in joining the lab, please contact Veijo.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator''" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator''" %}

{% include section.html %}
