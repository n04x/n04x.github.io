---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<ul>{% for item in site.data.navigation.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

<h1>This is Home</h1>
<div id="header">
    <header>
        <a href="https://n04x.github.io/kanto-money-run">Kanto Money Run</a>
    </header>
</div>