---
layout: index
title: Learning the Subway
---

<style type="text/css" media="screen">
  #navigation { display: none; }  
  ul#homepage-nav { padding-left: 0; }
  #homepage-nav li { list-style-type: none; padding: 0; margin: 2em 0 2em 0; width: 200px; line-height: 250%; }
  h1 a span { float: left; }
  a img { float: right; }
</style>

# Welcome to New York

If you are new to New York City, you will find yourself taking the subway in no time at all. The subway system in this city is designed not for tourists or newcomers, but for people who sort of know their way around and take it every day. The sooner you learn how to use the system, the less frustration you'll have.

<ul id="homepage-nav">
{% for post in site.posts %}
  <li>
    <h1><a href="{{ post.url }}"><img src="/images/lame-map.jpg"><span>{{ post.title }}</span></a></h1>
  </li>
{% endfor %}
</ul>