---
layout: default
---


<ul>
  {% for post in site.posts %}

<style>
    
       ul{list-style-type: none;}

</style>

    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

