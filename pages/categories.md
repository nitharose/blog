---
layout: default
title: Categories
---

# Blog Posts by Category

## 📱 Programming
Technical posts about coding, languages, and frameworks.

{% for post in site.posts %}
  {% if post.categories contains 'programming' %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}

## 💻 Technology
Technology trends, reviews, and insights.

{% for post in site.posts %}
  {% if post.categories contains 'technology' %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}

## 📚 Tutorials
Step-by-step guides and how-to articles.

{% for post in site.posts %}
  {% if post.categories contains 'tutorial' %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}

## ⚙️ System Administration
DevOps, servers, and infrastructure.

{% for post in site.posts %}
  {% if post.categories contains 'system-admin' %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}

---

[← Back to Home](/)
