---
layout: default
title: Idea Scout — AI-находки для разработчиков
---

<style>
  ul, ol {
    list-style: none !important;
    padding-left: 0 !important;
  }
  ul li::before, ol li::before {
    content: none !important;
  }
</style>

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

© Idea Scout 2026 [Telegram](https://t.me/idea_scout) | [VK](https://vk.com/idea_scout) | [Pinterest](https://ru.pinterest.com/idea_scout/) | [Дзен](https://dzen.ru/user/oeqyyrihxgh7qgytbd1nq4zy96k)