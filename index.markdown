---
layout: default
---
{% include analytics.html %}
{% include sidebar.html %}

## Hi there! :wave:

Welcome to my blog!
I’m a Brand Associate managing digital advertising operations.
I have a keen interest in learning and exploring all aspects of media agencies, with a focus on understanding the core of platforms like Google Ads, Meta Ads, DV360, and more.

## Posts

{% for post in site.posts %}

:bookmark_tabs: [ {{ post.title }} ]({{ post.url }})
{% endfor %}
