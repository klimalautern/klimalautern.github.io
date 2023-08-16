---
title: KlimaLautern - Blog
type: website
description: Blog von KlimaLautern
---

<div class="collection-items">

{% for post in site.posts %}
<a class="collection-items__item" href="{{ post.url }}">
    <div class="collection-items__preview">
    <span class="collection-items__label">{{ post.tags }}</span>
    <h2 class="collection-items__title">{{ post.title }}</h2>
	<img src="{{ post.thumbnail }}" loading="lazy" />
	<time class="collection-items__date" datetime="{{ post.date }}">
		{{ post.date | date: '%d.%m.%Y' }}
	</time>
  </div>
</a>
{% endfor %}

</div>
