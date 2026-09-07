---
layout: default
---

# مرحباً بكم في موقعي الجديد! 👋

هنا سأقوم بنشر مقالاتي وأفكاري باستمرار.

## 📝 أحدث المقالات:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
