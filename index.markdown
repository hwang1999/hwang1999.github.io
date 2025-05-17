---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<nav>
  <ul>
    {% for item in site.data.navigation.main %}
      <li><a href="{{ item.url | relative_url }}">{{ item.title }}</a></li>
    {% endfor %}
  </ul>
</nav>

<h1>Let's Study Together</h1>
<p>Ask Why?</p>
