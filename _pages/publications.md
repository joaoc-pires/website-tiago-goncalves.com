---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Published Articles
{% for post in site.publications reversed %}
  {% if post.papertype == "article" %}
<p style="line-height: 1;">
<span class="archive__subtitle" style="font-size: small;">{{ post.month }} {{ post.year }}</span><br>
<a class="post-link" href="{{ post.permalink }}">{{ post.title }}</a><br>
<span style="font-style: italic;">{{ post.venue }}</span>
</p>
  {% endif %}
{% endfor %}

## International Conference Proceedings
{% for post in site.publications reversed %}
  {% if post.papertype == "proceeding" %}
<p style="line-height: 1;">
<span class="archive__subtitle" style="font-size: small;">{{ post.month }} {{ post.year }}</span><br>
<a class="post-link" href="{{ post.permalink }}">{{ post.title }}</a><br>
<span style="font-style: italic;">{{ post.venue }}</span>
</p>
  {% endif %}
{% endfor %}
