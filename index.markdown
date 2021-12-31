---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#layout: home
layout: page
---
{% for prog in site.software %}
<p>
<a href="{{ prog.url | relative_url }}">
  {{ prog.title }}<br />
</a>
</p>
{% endfor %}