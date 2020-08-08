---
layout: portal
title: Portals
---

<div class="container"> 
 
    {%- include vwtab.html -%}

  <div class="row">
  
 {% for page in site.data.services %}
   <div class="row  shadow-sm p-3 mb-3 bg-white rounded" >
  <a href="{{ page.link }}"  target="_blank">
 
<div >  
  <img src="./img/{{ page.image }}" >  
</div>
<p>{{ page.name }}</p>
 
{{ page.text }}
</a>
  </div>
{% endfor %}

</div>
 
<!-- 
- name: GroupLearn
  image: grouplearn.png
  text: Lernportal
  link: https://groupwiki.vw.vwg -->
