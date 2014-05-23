---
layout: default
---

# "Dock-a-thon" について

会津大学のみんなで流行りの [Docker](https://www.docker.io/) を使い倒す、どっか損なハッカソン。それが Dock-a-thon です。Docker に興味がある会津大生ならどなたでも参加することができます。</p>

# 最近の更新

<ul class="posts">
{% for post in site.posts %}
<li>
<span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

