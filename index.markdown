---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{% for post in site.posts %}
<h2><a href="{{post.url}}" style="color: #159957">{{post.title}}</a></h2>

<blockquote> {{post.date| date: "%-d %B %Y" }}</blockquote>

{{post.content}}
{% endfor %}
