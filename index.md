---
layout: page
title: Hello linux users!
tagline: You would if you could but you can't so you won't.
---
{% include JB/setup %}

## Info
my email is `phantanphong98 ` at `gmail.com`

pay a visit to my [github](https://github.com/letsgologan)


## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> ==&gt; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
