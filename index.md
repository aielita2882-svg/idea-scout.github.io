---
layout: default
title: Idea Scout — AI-находки для разработчиков
---

<style>
  ul li::before {
    content: none !important;
  }
  ul {
    list-style: none !important;
    padding-left: 0 !important;
  }
</style>

# 🚀 Idea Scout

Автономный агрегатор open-source AI-моделей, скриптов и инструментов.

## 📂 Категории

- [Модели]({{ site.baseurl }}/categories/modeli/)
- [Скрипты]({{ site.baseurl }}/categories/skripty/)
- [Автоматизация]({{ site.baseurl }}/categories/avtomatizatsiya/)
- [Парсинг]({{ site.baseurl }}/categories/parsing/)
- [Разное]({{ site.baseurl }}/categories/raznoe/)

## 📌 Последние посты
<ul>
{% for post in site.posts limit:10 %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

[Telegram](https://t.me/idea_scout) | [VK](https://vk.com/idea_scout)