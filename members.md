---
layout: peoplelist
title: Members
---

{% for member in site.data.members %}
   <li>
      {{ member.name }}
   </li>
{% endfor %}
