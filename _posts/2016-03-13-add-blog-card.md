---
layout: post
title:  "3/13"
date:   2016-03-13 1:00:00 UTC+9
categories: newcategory
tags:
image: /images/pic04.jpg

blog-card-site: wikipedia.org
blog-card-url: hhttps://upload.wikipedia.org/
blog-card-image: https://upload.wikimedia.org/wikipedia/commons/7/75/Transparent_flag_with_question_mark.png
blog-card-site-title: はてなtest
blog-card-desc: hatena test </br> test

---

- include テスト

{% include image.html image-url="/images/pic01.jpg" image-alt="テスト" image-style="width: 100%;max-width: 600px" %}

- include テスト2 style
{% include image.html image-url="/images/pic02.jpg" image-alt="テスト2" %}

- include テスト3 url
{% include image.html image-alt="テスト3" image-style="width: 100%;max-width: 600px" %}

- include テスト4 url
{% include image.html image-url="" image-alt="test4" image-style="width: 100%;max-width: 600px" %}

- blogcardテスト

{% include blogcard.html %}

- tetete
