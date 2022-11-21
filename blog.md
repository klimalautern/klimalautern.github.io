---
title: KlimaLautern - Klimaentscheid Kaiserslautern - Blog
type: website
description: Blog von KlimaLautern - Klimaentscheid Kaiserslautern
---

{% for post in site.posts %}
   <a href="{{ post.url }}">{{ post.date | date: '%d.%m.%Y' }} - {{ post.title }}</a>
{% endfor %}

