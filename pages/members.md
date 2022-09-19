--
layout: peoplelist
title: Members
--

# List of FriquiFund actual members, sorted by some weird mechanism

{% for tag in site.data.people.json %}
   {% for item in tag %}
   <li>
      {{ item }}
   </li>
   {% endfor %}
{% endfor %}
