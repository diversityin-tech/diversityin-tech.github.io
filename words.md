---
layout: default
title: Words
---

# Words

### In each episode guests are asked about a **word** describing the world they want to live in. You can see their answers below. A click on a [#hashtag]() will navigate you to the corresponding episode.

# What word describes best the **tech world** you want to live in?


<p>
<ul>
{%- for post in site.posts -%}
{% if post.word != null %}
<li>
<h2>
<a href="{{post.url}}">
#{{ post.word }}
</a>
</h2>
</li>
{%- endif -%}
{%- endfor -%}
</ul>
</p>
