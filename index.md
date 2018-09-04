---
layout: home
---

## Hey there! 👋

I'm Kyle Macey. I like software, paintball, and riding my bike. I work at this neat place called [GitHub](https://github.com/about) on the Data Portability team. We write tools (mostly using [Ruby](https://www.ruby-lang.org/)) that help make it easier for developers to free their data!

I'm based in Rochester, NY: ask me about [Garbage Plates](https://www.huffingtonpost.com/2014/02/26/garbage-plate_n_4854514.html) and [Genny Cream Ales](https://www.geneseebeer.com/beer/genesee-cream/)!

I like talking about interpersonal relationships, mental wellness in tech, and intersectional feminism. I don't do a *lot* on social media, but you can hit me up on [Twitter](https://twitter.com/itskylemacey) and get me chatting.


## My recent(ish) blog posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}
