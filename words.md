---
layout: default
title: Words
---

## What word describes best the **tech world** you want to live in?

In each episode guests are asked about a **word** describing the world they want to live in. What words did they choose? See them below and click on the links to navigate to their corresponding episodes.

<p>
{%- for post in site.posts -%}
{% if post.word != null %}
<a href="{{post.url}}">
<h2> #{{ post.word }}</h2>
</a>
{%- endif -%}
{%- endfor -%}
</p>
