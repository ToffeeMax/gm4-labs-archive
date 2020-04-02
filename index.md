---
layout: default
---
{% for group in site.data.navigation.groups %}
## {{ group.title | capitalize }}
<ul>
   {% for item in group.pages %}
      <li><a href="channels/Gamemode%204%20Labs%20-%20{{ item.channel }}%20%5B{{ item.id }}%5D.html">{{ item.title }}</a></li>
   {% endfor %}
</ul>
{% endfor %}
