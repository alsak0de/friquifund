--
layout: peoplelist
title: Members
--

# List of FriquiFund actual members, care to join us?


   
    
      {% for member in site.data.members %}
      <div class="badge-base LI-profile-badge" d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center data-locale="es_ES" data-size="small" data-theme="light" data-type="VERTICAL" data-vanity="{{member.lnkdnuser}}" data-version="v1"><a class="badge-base__link LI-simple-link" href="{{member.badgelink}}">{{member.name}}</a></div>
     
      {% endfor %}
      

