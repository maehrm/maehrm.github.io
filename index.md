---
layout: page
title: Masahide Maehara's Web Page!
tagline: 
---
{% include JB/setup %}
## はじめに
GitHub Pages を利用して、Jekyll + Jekyll Bootstrap の練習を始めてみました。何かおかしな点などありましたら、twitter([@maehrm](https://twitter.com/maehrm))ででもご指摘いただければ幸いです。

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



