---
redirect_from: /verein/news.shtml
---

## News

{% for news in site.posts %}
<article>
	<h3>{{ news.date | date: "%d.%m.%Y" }}</h3>
	<section class="indented">{{ news.content }}</section>
</article>
{% endfor %}