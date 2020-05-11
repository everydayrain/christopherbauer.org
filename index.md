---
layout: default
---


[About](./another-page.html).[CV](./another-page2.html)

There should be whitespace between paragraphs.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

