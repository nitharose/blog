---
layout: default
title: Home
---

# Welcome to My Technical Blog 🚀

Hello! I'm sharing my technical insights, tutorials, and coding adventures here.

## Latest Posts

{% for post in site.posts limit:5 %}
- **[{{ post.title }}]({{ post.url }})** - *{{ post.date | date: "%B %d, %Y" }}*
  - Category: `{{ post.categories | join: ', ' }}`
  
{% endfor %}

---

## Browse by Category

### 📱 Programming
Posts about programming languages, frameworks, and best practices.

### 💻 Technology
Technology trends, reviews, and insights.

### 📚 Tutorials
Step-by-step guides and how-to articles.

### ⚙️ System Administration
DevOps, servers, and infrastructure topics.

---

**[View All Posts →](/categories/)**
