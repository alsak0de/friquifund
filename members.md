---
layout: peoplelist
title: Members
---

# Here comes the sun, durun-durun

<table>
    <tr>
    <th>Name</th>
    <th>Purpose</th>
    <th>Badge</th>     
  </tr>
  
  
{% for member in site.data.members %}
    <tr>
      <td>member.name</td>
      <td>member.purpose</td>
      <td>El badge</td>
    </tr>
{% endfor %}
</table>


