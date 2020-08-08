---
layout: portal
title: Portals 
---

<div class="container"> 


    {%- include vwtab.html -%}

  <div class="row">

 
 
  <div class="row d-flex justify-content-center" >



 {% for page in site.data.appbiegerSections %}
 
  <a href="{{ page.link }}"  target="_blank" class="btn ">
 
<div class="shadow-sm p-3 mb-3 bg-white rounded" style="width: 10rem;">  
  <img class="" src="./img/{{ page.image }}" alt="Card image cap">  
</div>
<p class="text-secondary">{{ page.name }}</p>

</a>



{% endfor %}

  </div>
</div>
 